# EZPZtags
This plugin aims at being a complete tag management plugin for vim. So far only C is supported.

Features:

* generation of a local vimrc file to include only project-related system tags
* creation of system tag files in ~/.vim/tags
* project tag file generation
* local vimrc management, e.g. the plugin will not overwrite .lvimrc, but rather, manage it's own configuration section. This is useful because .lvimrc can be used for other reasons.

This script is based on https://www.vim.org/scripts/script.php?script_id=3710
