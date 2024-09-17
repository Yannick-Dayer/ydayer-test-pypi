<!-- SPDX-FileCopyrightText: Copyright © Idiap Research Institute <contact@idiap.ch>

SPDX-License-Identifier: MIT -->
# Test package for PyPI publishing

This is a simple paragraph describing the project.

## Full URL link

This is another paragraph with a [link to a page](https://www.example.com).
The link should point to `https://www.example.com`

## Link to local file

The following links point to an image in the repository: [image](img/test.png), [same image again](./img/test.png).
The links should all point to `https://raw.githubusercontent.com/Yannick-Dayer/ydayer-test-pypi/img/test.png`.

## Link to local directory

The following links point to an directory in the repository: [dir](img/), [same dir](./img), [same dir again](./img/).
The links should all point to `https://github.com/Yannick-Dayer/ydayer-test-pypi/tree/img`.

## "Embedded" images

The following objects should be all be images correctly displayed:

![This should be an image| 100x100 ](img/test.png) ![This should be an image](./img/test.png)

The following objects should link to `https://www.example.com`:

[![This should be an image](img/test.png)](https://www.example.com)

And the following objects should link to a file in the repository (`https://raw.githubusercontent.com/Yannick-Dayer/ydayer-test-pypi/img/test.png`):

[![This should be an image](img/test.png)](img/test.png)

**Bonus**: resizable image with inline html:

<img src="img/test.png" height="64">
