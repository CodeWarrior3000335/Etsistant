# Contributing to Etsistant

This guide keeps both developers working through the same branch and pull request process.

## Branches

- `main` is the deployable branch and the source used for production deployment. Keep it stable and do not push directly to it.
- `develop` is the shared integration branch for completed work before release.
- Create one short-lived feature branch per Trello card from `develop`, using `feature/<card-id>-<short-description>`. For example: `feature/B-03-upload-endpoint`.

## Pull request workflow

1. Update your local `develop` branch and create a feature branch from it.
2. Make the change for the card on that feature branch. Keep the pull request focused on that work.
3. Open a pull request from the feature branch into `develop` and include the Trello card ID and a concise summary.
4. Ask the other developer to review the pull request. Address feedback and ensure relevant checks pass before merging.
5. Delete the feature branch after it has been merged.
6. When `develop` is ready for a release, open a pull request from `develop` into `main`. Get review and ensure checks pass before merging.

The initial project setup may initialize `main` directly. After that, do not commit or push directly to `main`, or merge unreviewed changes into it. Keep `main` deployable at all times.
