# Aip-man Custom Packages

## Description

There are some problems with using AppImages:

- Not every software is available as an AppImage, but there are some I want.
- There are also some continuous build AppImages, which means a tool like aip-man will not have a static link to a version. Until the link is uploaded in the repo, people will lose access

Thus, there needs to be a place to store custom AppImages for aip-man and to have static link between repo updates.

Each branch here is a different AppImage with a given version.

You can't store all of them in one branch because of size restrictions, and if it's in release then not everyone can update it, so that's why it's a branch per AppImage

