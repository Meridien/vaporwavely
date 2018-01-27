![Vaporwavely](https://raw.githubusercontent.com/Owanesh/vaporwavely/master/logo.png)
---
[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)


Convert your text in an aesthetical text, or generate nostalgic 1999 paragraphs with vaporipsum


## How to use 👾


- `vaporipsum` : Generate a random text, like [Lorem Ipsum](https://www.lipsum.com/), but more nostalgic and aesthetic

    ```py
    from vaporwavely import vaporipsum

    vaporipsum(4) # it generates 4 paragraphs of random text
    ```


- `vaporize` : Convert your text from this **Hello World** to this **Ｈｅｌｌｏ Ｗｏｒｌｄ**

    ```py
    from vaporwavely import vaporize

    mystring = "Hi Owanesh"
    vaporize(mystring) # Ｈｉ Ｏｗａｎｅｓｈ
    ```
### Use combo for an ａｅｓｔｈｅｔｉｃ results 🦄

- **Vaporize your vaporipsum**

    ```py
    from vaporwavely import vaporize, vaporipsum

    print(vaporize(vaporipsum(4)))
    ```
- **Do it upper**
    ```py
    from vaporwavely import vaporize

    vaporize('get me upper and vaporized').upper()
    ```
    ＧＥＴ ＭＥ ＵＰＰＥＲ ＡＮＤ ＶＡＰＯＲＩＺＥＤ

### Contribute 🎖
*Ｒｅａｌｌｙ ｍａｎ?*

First of all thanks if you want help me. Below there are requirements and steps for testing

    pip install vaporwavely/tests/requirements.txt
    nosetests --with-coverage --cover-package=vaporwavely


---
#### Credits 🙏
Thanks to [TristanAG](https://github.com/TristanAG/vaporipsum) for Vaporipsum idea

