# Reference

<!-- DO NOT EDIT: This document was generated by Puppet Strings -->

## Table of Contents

### Classes

* [`vim`](#vim): This module manages Vim

## Classes

### <a name="vim"></a>`vim`

This module manages Vim

#### Examples

##### 

```puppet
include vim
```

#### Parameters

The following parameters are available in the `vim` class:

* [`package_provider`](#package_provider)
* [`package_list`](#package_list)
* [`root_vimrc_source`](#root_vimrc_source)
* [`root_vimrc_path`](#root_vimrc_path)
* [`root_vimrc_owner`](#root_vimrc_owner)
* [`root_vimrc_group`](#root_vimrc_group)
* [`root_vimrc_mode`](#root_vimrc_mode)
* [`root_vim_dir_source`](#root_vim_dir_source)
* [`root_vim_dir_path`](#root_vim_dir_path)
* [`root_vim_dir_owner`](#root_vim_dir_owner)
* [`root_vim_dir_group`](#root_vim_dir_group)
* [`root_vim_dir_mode`](#root_vim_dir_mode)

##### <a name="package_provider"></a>`package_provider`

Data type: `Optional[String[1]]`

The puppet provider to be used for the package resources.

Default value: ``undef``

##### <a name="package_list"></a>`package_list`

Data type: `Array[String[1]]`

List of vim packages to be present.

Default value: `['vim-common', 'vim-enhanced']`

##### <a name="root_vimrc_source"></a>`root_vimrc_source`

Data type: `String[1]`

Value of the source parameter used in the file resource for managing
`.vimrc`.

Default value: `'vim/vimrc'`

##### <a name="root_vimrc_path"></a>`root_vimrc_path`

Data type: `Stdlib::Absolutepath`

Path to the `.vimrc` configuration file.

Default value: `'/root/.vimrc'`

##### <a name="root_vimrc_owner"></a>`root_vimrc_owner`

Data type: `String[1]`

Owner of the `.vimrc` file.

Default value: `'root'`

##### <a name="root_vimrc_group"></a>`root_vimrc_group`

Data type: `String[1]`

Group of the `.vimrc` file.

Default value: `'root'`

##### <a name="root_vimrc_mode"></a>`root_vimrc_mode`

Data type: `Stdlib::Filemode`

Mode of the `.vimrc` file.

Default value: `'0644'`

##### <a name="root_vim_dir_source"></a>`root_vim_dir_source`

Data type: `String[1]`

Value of the source parameter used in the file resource for managing the
`.vim` directory.

Default value: `'vim/vim'`

##### <a name="root_vim_dir_path"></a>`root_vim_dir_path`

Data type: `Stdlib::Absolutepath`

Path to the `.vim` directory.

Default value: `'/root/.vim'`

##### <a name="root_vim_dir_owner"></a>`root_vim_dir_owner`

Data type: `String[1]`

Owner of the `.vim` directory.

Default value: `'root'`

##### <a name="root_vim_dir_group"></a>`root_vim_dir_group`

Data type: `String[1]`

Group of the `.vim` directory.

Default value: `'root'`

##### <a name="root_vim_dir_mode"></a>`root_vim_dir_mode`

Data type: `Stdlib::Filemode`

Mode of the `.vim` directory.

Default value: `'0644'`

