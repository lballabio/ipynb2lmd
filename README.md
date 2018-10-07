
This is the script that I used to convert the Jupyter notebooks in the
[QuantLib Python Cookbook](https://leanpub.com/quantlibpythoncookbook)
into the Leanpub-flavored Markdown files required for publication with
Leanpub.

#### Usage

The script must be passed the name of the notebook to convert and the
name of the output directory (which must already exist); for instance,
running

    python ipynb2lmd.py example.ipynb output/

in this folder will create `example.md` in the `output` directory,
along with a pair of figures (also extracted from the notebook) that
the notebook contains and the Markdown file includes.

#### License

This script is released under the 3-Clause BSD license; see
[LICENSE](LICENSE) for details.

#### Support (or lack thereof)

I hope you'll find this script useful, but I won't provide support for
it.  You're welcome to fork it and improve it.

