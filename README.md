# SCZR - serwer tcp wyświetlający obrazy

## Instalacja

```
~ ❯❯❯ pip install --user sczr_tcp
Collecting sczr_tcp
  Using cached sczr_tcp-0.1.2-py3-none-any.whl (2.8 kB)
Requirement already satisfied: loguru<0.6.0,>=0.5.3 in ./.local/lib/python3.9/site-packages (from sczr_tcp) (0.5.3)
Requirement already satisfied: typer<0.4.0,>=0.3.2 in ./.local/lib/python3.9/site-packages (from sczr_tcp) (0.3.2)
Requirement already satisfied: pygame<3.0.0,>=2.0.0 in ./.local/lib/python3.9/site-packages (from sczr_tcp) (2.0.0)
Requirement already satisfied: pydantic<2.0.0,>=1.7.3 in ./.local/lib/python3.9/site-packages (from sczr_tcp) (1.7.3)
Requirement already satisfied: orjson<4.0.0,>=3.4.6 in ./.local/lib/python3.9/site-packages (from sczr_tcp) (3.4.6)
Requirement already satisfied: click<7.2.0,>=7.1.1 in /usr/lib/python3.9/site-packages (from typer<0.4.0,>=0.3.2->sczr_tcp) (7.1.2)
Installing collected packages: sczr-tcp
Successfully installed sczr-tcp-0.1.2
```

## Pomoc

```
pygame 2.0.0 (SDL 2.0.12, python 3.9.0)
Hello from the pygame community. https://www.pygame.org/contribute.html
Usage: sczr-tcp [OPTIONS]

Options:
  --host TEXT                     [default: 0.0.0.0]
  --port INTEGER                  [default: 9000]
  --width INTEGER                 [default: 1000]
  --height INTEGER                [default: 300]
  --buffer-size INTEGER           [default: 20480]
  --install-completion [bash|zsh|fish|powershell|pwsh]
                                  Install completion for the specified shell.
  --show-completion [bash|zsh|fish|powershell|pwsh]
                                  Show completion for the specified shell, to
                                  copy it or customize the installation.

  --help                          Show this message and exit.
```

## Użycie

```
~ ❯❯❯ sczr-tcp
pygame 2.0.0 (SDL 2.0.12, python 3.9.0)
Hello from the pygame community. https://www.pygame.org/contribute.html
2020-12-16 06:34:26.184 | INFO     | sczr_tcp.cli:run:84 - Listening on 0.0.0.0:9000
```

## Moduł C++

https://gist.github.com/0471e852599f9c984ececebeec332ebf