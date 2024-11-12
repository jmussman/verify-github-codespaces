[//]: # (README.md)
[//]: # (Copyright © 2024 Joel A Mussman. All rights reserved.)
[//]: #

![Banner Light](https://raw.githubusercontent.com/jmussman/cdn-fun/main/banners/banner-verify-github-codespaces-light.png#gh-light-mode-only)
![banner Dark](https://raw.githubusercontent.com/jmussman/cdn-fun/main/banners/banner-verify-github-codespaces-dark.png#gh-dark-mode-only)

# Verify GitHub Codepaces is accessible from your computer

## Overview

The purpose of this project is to verify that Github Codespaces is accessible from your computer.
Enterprise networks and virtual private networks (VPNs) may sometimes block GitHub Codespaces to prevent data leakage.
This example uses Codetour, which is a Visual Studio Code extension that takes the user on a tour of a project.

## Configuration

1. Sign-on to GitHub using your personal account.
1. On the main page of the respository for this project click the green "Code" button at the upper right.
1. Select the "Codespaces"  tab, and click the green "Create codespace on main" button.
This will launch a new tab in your browser, wait for it to competely load.
1. If the Codetour and landing page opens in the started codespace without an error, Github Codespaces is accessible.
If you see an error, e.g. the codespace disconnected, then GitHub Codespaces is not accessible from your environment.

## Verification and Teardown

If you are looking at this README.md file in a codespace, everything is OK.
You can tell you are in a codespace if the browser address bar contains a funky name like "orange-waffle-xxxxxxxx" (just an example).
A codetour should have opened with instructions, but since it may not have follow these:

* In the other browser tab refresh the repository window.
* Click the \"Code\" button and select the \"Codespace\" tab.
* Use the delete option to remove this codespace.
* Close this codespace window.

## License

The code is licensed under the MIT license. You may use and modify all or part of it as you choose, as long as attribution to the source is provided per the license. See the details in the [license file](./LICENSE.md) or at the [Open Source Initiative](https://opensource.org/licenses/MIT).


<hr>
Copyright © 2024 Joel A Mussman. All rights reserved.