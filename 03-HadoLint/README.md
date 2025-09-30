# Hadolint
## Basic Commands
* hadolint /path/to/Dockerfile
* hadolint /path/to/Dockerfile --ignore DL3006
* hadolint /path/to/Dockerfile -t error
* hadolint /path/to/Dockerfile --error DL3006
* hadolint /path/to/Dockerfile --no-fail
* echo $? (On Mac)
* $LastExitCode (On Windows PowerShell)

## Using Hadolint.yaml
* hadolint --config /path/to/config.yaml Dockerfile
* Inline Ignore
    ```
    # hadolint ignore=DL3006
    FROM debian
    ```

## Using Container
* docker pull hadolint/hadolint
* docker run --rm -i hadolint/hadolint < Dockerfile