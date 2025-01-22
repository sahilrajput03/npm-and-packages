# NPM and Packages

To install a folder as a dependency in a project (e.g, `folder2`) you can simply go to `folder2` run `cd folder2 && npm i ../folder1`. This will add `"folder1": "file:../folder1"` under `dependencies` key in your `package.json`. This only needs to be done only **_ONCE_**.

In future you only need to run `npm i` in `folder2` to create a symmlink folder of `folder1` in your `node_modules`.
