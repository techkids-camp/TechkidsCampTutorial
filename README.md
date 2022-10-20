# TechkidsCAMP

テックキッズスクールのテスト

## タイトル１のテスト

本文のテスト

* [github](https://github.com/maple-1031/TechkidsCampTutorial) にmdファイルをアップロードすると、
* **Github Action** がスタートして、
* およそ*7分*で
* [makecode](https://minecraft.makecode.com/#tutorial:https://github.com/maple-1031/TechkidsCampTutorial) にアップロードされます。

## タイトル２のテスト

![](https://raw.githubusercontent.com/maple-1031/TechkidsCampTutorial/master/images/TKC_1408x300.png)

> [http://arcade.makecode.com/#tutorial:https://github.com/microsoft/pxt-tutorial-sample](http://arcade.makecode.com/#tutorial:https://github.com/microsoft/pxt-tutorial-sample)

The url should be formatted as follows: `https://[editor URL]/#tutorial:[github-username]/[github-repository-name]`

You can also include additional tutorials in one repository. In this case, the `first-tutorial.md` and `second-tutorial.md`. If you add a new file, make sure it is included in the `files` list in `pxt.json`. If you add this file from the MakeCode Editor, it will be automatically updated. You can view these tutorials at the following URLs:

> [http://arcade.makecode.com/#tutorial:https://github.com/microsoft/pxt-tutorial-sample/first-tutorial](http://arcade.makecode.com/#tutorial:https://github.com/microsoft/pxt-tutorial-sample/first-tutorial)

> [http://arcade.makecode.com/#tutorial:https://github.com/microsoft/pxt-tutorial-sample/second-tutorial](http://arcade.makecode.com/#tutorial:https://github.com/microsoft/pxt-tutorial-sample/second-tutorial)

The url should be formatted as follows: `https://[editor URL]/#tutorial:[github-username]/[github-repository-name]/[path-to-tutorial]`

## Custom Blocks

A repository containing a tutorial may also contain custom blocks for use in the tutorial. The `custom.ts` file here exports two functions as blocks. These blocks can then be used in any tutorial in the same repository. As with new tutorial files, make sure any new TypeScript files are added to the list in `pxt.json`.

## Custom Localization

Localized versions of the tutorial can also be added to the repository, under a `_locales` folder. This folder contains a list of sub-directories with the correctly capitalized language code (eg. zh-CN, de-DE). The localized tutorial should have the same file name as the base tutorial. To view a localized version of the tutorial, add `?lang=[language-code]` to the URL, as follows:

> [http://arcade.makecode.com?lang=zh-CN#tutorial:https://github.com/microsoft/pxt-tutorial-sample/first-tutorial](http://arcade.makecode.com?lang=zh-CN#tutorial:https://github.com/microsoft/pxt-tutorial-sample/first-tutorial)

## Creating a Release

When you update the Github repository, it make take up to 20 minutes for your changes to be reflected in the MakeCode editor, due to caching. To force an update, you will need to create a "release":

* Open [https://arcade.makecode.com/](https://arcade.makecode.com/) (or makecode.microbit.org, minecraft.makecode.com)
* Click on **Import** on the right-hand side above the row of your projects
* Select **Your Github Repo** and sign into Github if prompted
* Select the repository with your tutorial
* In the MakeCode editor, click the **Github Icon** on the bottom toolbar by the project name
* In the **Release Zone** section of the page, click **Create a Release** and select whichever release type feels most appropriate.
