# Notes

[my profile](https://vscode.dev/profile/github/37730646daf7aa08bb449a757ad476fe)

```bash
(base) PS D:\Projects> devcontainer up --workspace-folder ./devcontainer up --workspace-folder vscode-remote-try-rust
devcontainer up

Create and run dev container

Options:
  --help                            Show help                                                                  [boolean]
  --version                         Show version number                                                        [boolean]
  --docker-path                     Docker CLI path.                                                            [string]
  --docker-compose-path             Docker Compose CLI path.                                                    [string]
  --container-data-folder           Container data folder where user data inside the container will be stored.  [string]
  --container-system-data-folder    Container system data folder where system data inside the container will be stored.
                                                                                                                [string]
  --workspace-folder                Workspace folder path. The devcontainer.json will be looked up relative to this path
                                    .                                                                           [string]
  --workspace-mount-consistency     Workspace mount consistency.
                                                      [choices: "consistent", "cached", "delegated"] [default: "cached"]
  --mount-workspace-git-root        Mount the workspace using its Git root.                    [boolean] [default: true]
  --id-label                        Id label(s) of the format name=value. These will be set on the container and used to
                                     query for an existing container. If no --id-label is given, one will be inferred fr
                                    om the --workspace-folder path.                                             [string]
  --config                          devcontainer.json path. The default is to use .devcontainer/devcontainer.json or, if
                                     that does not exist, .devcontainer.json in the workspace folder.           [string]
  --override-config                 devcontainer.json path to override any devcontainer.json in the workspace folder (or
                                     built-in configuration). This is required when there is no devcontainer.json otherw
                                    ise.                                                                        [string]
  --log-level                       Log level for the --terminal-log-file. When set to trace, the log level for --log-fi
                                    le will also be set to trace.  [choices: "info", "debug", "trace"] [default: "info"]
  --log-format                      Log format.                              [choices: "text", "json"] [default: "text"]
  --terminal-columns                Number of rows to render the output for. This is required for some of the subprocess
                                    es to correctly render their output.                                        [number]
  --terminal-rows                   Number of columns to render the output for. This is required for some of the subproc
                                    esses to correctly render their output.                                     [number]
  --default-user-env-probe          Default value for the devcontainer.json's "userEnvProbe".
         [choices: "none", "loginInteractiveShell", "interactiveShell", "loginShell"] [default: "loginInteractiveShell"]
  --update-remote-user-uid-default  Default for updating the remote user's UID and GID to the local user's one.
                                                                         [choices: "never", "on", "off"] [default: "on"]
  --remove-existing-container       Removes the dev container if it already exists.           [boolean] [default: false]
  --build-no-cache                  Builds the image with `--no-cache` if the container does not exist.
                                                                                              [boolean] [default: false]
  --expect-existing-container       Fail if the container does not exist.                     [boolean] [default: false]
  --skip-post-create                Do not run onCreateCommand, updateContentCommand, postCreateCommand, postStartComman
                                    d or postAttachCommand and do not install dotfiles.       [boolean] [default: false]
  --skip-non-blocking-commands      Stop running user commands after running the command configured with waitFor or the
                                    updateContentCommand by default.                          [boolean] [default: false]
  --prebuild                        Stop after onCreateCommand and updateContentCommand, rerunning updateContentCommand
                                    if it has run before.                                     [boolean] [default: false]
  --user-data-folder                Host path to a directory that is intended to be persisted and share state between se
                                    ssions.                                                                     [string]
  --mount                           Additional mount point(s). Format: type=<bind|volume>,source=<source>,target=<target
                                    >[,external=<true|false>]                                                   [string]
  --remote-env                      Remote environment variables of the format name=value. These will be added when exec
                                    uting the user commands.                                                    [string]
  --cache-from                      Additional image to use as potential layer cache during image building      [string]
  --buildkit                        Control whether BuildKit should be used [choices: "auto", "never"] [default: "auto"]
  --additional-features             Additional features to apply to the dev container (JSON as per "features" section in
                                     devcontainer.json)                                                         [string]
  --skip-post-attach                Do not run postAttachCommand.                             [boolean] [default: false]
  --dotfiles-repository             URL of a dotfiles Git repository (e.g., https://github.com/owner/repository.git)
                                                                                                                [string]
  --dotfiles-install-command        The command to run after cloning the dotfiles repository. Defaults to run the first
                                    file of `install.sh`, `install`, `bootstrap.sh`, `bootstrap`, `setup.sh` and `setup`
                                     found in the dotfiles repository`s root folder.                            [string]
  --dotfiles-target-path            The path to clone the dotfiles repository to. Defaults to `~/dotfiles`.
                                                                                        [string] [default: "~/dotfiles"]
  --container-session-data-folder   Folder to cache CLI data, for example userEnvProb results                   [string]

(base) PS D:\Projects>

```
