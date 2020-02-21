# Terraform 0.12 support for Atom based on original [language-terraform](https://github.com/GiantToast/language-terraform)

Adds syntax highlighting for Terraform 0.12 configuration files based on original [language-terraform](https://github.com/GiantToast/language-terraform) with some [improvement PRs](https://github.com/GiantToast/language-terraform/pulls) merged to Atom.

**Please remember to uninstall original [language-terraform](https://github.com/GiantToast/language-terraform) before to avoid conflicts!**

## Why a new package?

*I would be super happy to merge the changes necessary for Terraform 0.12 into the original [language-terraform](https://github.com/GiantToast/language-terraform)!*

Many people want the compatibility according to https://github.com/GiantToast/language-terraform/issues/42 but in the past a lot of useful and mergable [improvement PRs](https://github.com/GiantToast/language-terraform/pulls) did not get merged into the original [language-terraform](https://github.com/GiantToast/language-terraform) and I wanted to provide a way for people to use this now.

## Installation

Available as [Atom package](https://atom.io/packages/language-terraform-12):

```
apm uninstall language-terraform && apm install language-terraform-12
```

Or directly via git:

```
git clone https://github.com/cmur2/language-terraform-12.git ~/.atom/packages/language-terraform-12
```

## License

language-terraform-12 is licensed under the MIT License. See LICENSE for more information.
