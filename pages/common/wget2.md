# wget2

> A successor of wget, a file and recursive website downloaded
> More information: <>https://gitlab.com/gnuwget/wget2>.

- Download the contents of a URL to a file (named "foo" in this case):

`wget2 {{https://example.com/foo}}`

- Download the contents of a URL to a file in multithreaded chunks:

`wget2 {{https://example.com/foo}} --chunk-size=10M`

- Download all URLs stored in a text file to a specific directory:

`wget2 --directory-prefix {{path/to/directory}} --input-file {{URLs.txt}}`

- Download all URLs stored in a text file to a specific directory in parallel:

`wget2 --directory-prefix {{path/to/directory}} --input-file {{URLs.txt}}`

- Show download progress:

`wget2 --directory-prefix {{path/to/directory}} --input-file {{URLs.txt}} --progress=bar`
