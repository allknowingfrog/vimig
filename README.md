# vimig
Find and open migration files in Vim.

## Setup
Clone this repository and add the vimig executable to your path.

## Usage
Running `vimig` without arguments will open the migrations with the most recent timestamp. To open something else, pass part of the file name and choose from the list of matching migrations, i.e. `vimig create` will present a list of migrations whose file name contains "create".
