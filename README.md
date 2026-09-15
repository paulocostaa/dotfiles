# dotfiles

Personal configuration files for the tools and applications I use.

## Structure

```text
dotfiles/
└── .config/
    └── ...
```

The `.config/` directory contains the application configuration files.

## Install

Clone the repository:

```bash
git clone https://github.com/paulocostaa/dotfiles.git
cd dotfiles
```

Copy the configurations to your home directory:

```bash
mkdir -p ~/.config
cp -r .config/* ~/.config/
```

Review the files before applying them to an existing setup.

## Update

Pull the latest changes and copy the configs again:

```bash
git pull
cp -r .config/* ~/.config/
```

## Disclaimer

This README was generated with the help of AI.

## License

No license file is currently present in the repository.
