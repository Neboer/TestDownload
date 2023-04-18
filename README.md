# SimpleGitHubActionsReverseShell

欢迎使用使用 GitHub Actions 实现反向 shell 的项目！

该项目基于 GitHub Actions，可以帮助您在需要时获得远程 shell 访问权限，使您可以在不同的计算机之间远程执行命令。

使用本项目之前，您需要准备以下信息：

在您的 GitHub 账户下创建一个新的密钥对，并将公钥（PUBLIC_KEY）添加到 fork 的仓库的 Secrets 中。

您需要将远程 SSH 服务监听的端口（REMOTE_SSH_LISTEN_PORT）设置为一个未被占用的端口，以便在需要时使用。

您需要设置服务器的地址（SERVER_ADDR）、密码（SERVER_PASS）和端口（SERVER_PORT）。

设置好以上信息后，您只需将此项目 fork 到您的仓库中，并在 Secrets 中设置好上述的环境变量即可使用。

请注意，反向 shell 可能存在一些安全风险，使用前请确保您了解其工作原理，并谨慎使用。
