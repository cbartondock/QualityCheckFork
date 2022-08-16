# Fork of Quality Check Plugin

## Motivation

This fork has an additional function which allows one to automatically fix the cases of filenames and foldernames on windows so that they match exactly with what is present in Calibre's database.

This isn't necessary if you are only working with windows, but if you would like to be able to copy your library to a posix filesystem that is case sensitive then it is extremely important.

## Use

`> Quality Check > Fix > Check and re-case book paths`

The operation is idempotent, that is to say running it again will leave the library unchanged if no new files have been added.

⚠️⚠️ This operation is one way!
⚠️⚠️ We are changing file paths here. Use at your own risk, back up your library first.
