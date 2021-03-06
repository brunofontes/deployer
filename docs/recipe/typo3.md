<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/typo3.php -->
<!-- Then run bin/docgen -->

# typo3

[Source](/recipe/typo3.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`typo3_webroot`](#typo3_webroot)
  * [`shared_dirs`](#shared_dirs)
  * [`shared_files`](#shared_files)
  * [`writable_dirs`](#writable_dirs)
* Tasks
  * [`deploy`](#deploy)

## Config
### typo3_webroot
[Source](/recipe/typo3.php#L9)

DocumentRoot / WebRoot for the TYPO3 installation

### shared_dirs
[Source](/recipe/typo3.php#L32)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`

Shared directories

### shared_files
[Source](/recipe/typo3.php#L41)

* Overrides [`shared_files`](/docs/recipe/common.md#shared_files) from `recipe/common.php`

Shared files

### writable_dirs
[Source](/recipe/typo3.php#L48)

* Overrides [`writable_dirs`](/docs/recipe/common.md#writable_dirs) from `recipe/common.php`

Writeable directories


## Tasks
### deploy
[Source](/recipe/typo3.php#L14)

Main TYPO3 task

This task is group task which contains next tasks:
* [`deploy:info`](/docs/recipe/deploy/info.md#deployinfo)
* [`deploy:setup`](/docs/recipe/deploy/setup.md#deploysetup)
* [`deploy:lock`](/docs/recipe/deploy/lock.md#deploylock)
* [`deploy:release`](/docs/recipe/deploy/release.md#deployrelease)
* [`deploy:update_code`](/docs/recipe/deploy/update_code.md#deployupdate_code)
* [`deploy:shared`](/docs/recipe/deploy/shared.md#deployshared)
* [`deploy:vendors`](/docs/recipe/deploy/vendors.md#deployvendors)
* [`deploy:writable`](/docs/recipe/deploy/writable.md#deploywritable)
* [`deploy:symlink`](/docs/recipe/deploy/symlink.md#deploysymlink)
* [`deploy:unlock`](/docs/recipe/deploy/lock.md#deployunlock)
* [`deploy:cleanup`](/docs/recipe/deploy/cleanup.md#deploycleanup)


