# BEMJSON snippets for Sublime

Write BEMSJON faster.

![gif](http://i59.tinypic.com/2cn9xe0.gif)

## Install

**var1.** Use `Package Control` -> `BEMJSON snippets`

**var2.** Download, unzip, put to  `~Library\Application Support\Sublime Text 3`

## Usage

### Blocks <a name="blocks"></a>
**b** – BEM block

    {
        block : '${1:name}',
        content : [
            $0
        ]
    }


**btc** - BEM block with text content

    {
        block : '${1:name}',
        content : '$0'
    }


**bwt** - BEM block with tag mod

    {
        block : '$1',
        tag : '$2',
        content : [
            $0
        ]
    }


**bfc** - BEM block with function content

    {
        block : '$1',
        content : (function () {
            return $0;
        })()
    }


### Elements
**e** - BEM elem

    {
        elem : '$1',
        content : [
            $0
        ]
    }

**etc** - BEM elem with text content

    {
        elem : '$1',
        content : '$0'
    }


**ewt** - BEM elem with tag mod

    {
        elem : '$1',
        tag : '$2',
        content : [
            $0
        ]
    }


**efc** - BEM elem with function content

    {
        elem : '$1',
        content : (function () {
            return $0;
        })()
    }


### Mods
**t** - BEM tag mod

    tag : '$1',


**js** – BEM js mod

    js : { $1 : '$2' },


**mo** - BEM mods mod

    mods : { $1 : '$2' },


**mi** - BEM mix mod

    mix : [ { $1 : '$2' } ],


**a** - BEM attrs mod

    attrs : { $1 : '$2' },

### Links

For ATOM users = [atom-bemjson-snippets](https://github.com/verybigman/atom-bemjson-snippets)

