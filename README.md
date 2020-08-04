# make-static

## Usage
```
make-static http://website.com
```

## Options

```
Scrape a website and create an offline browsable version on the disk

Usage:
  make-static http://website.com [flags]

Flags:
      --config string         config file (default is $HOME/.goscrape.yaml)
  -d, --depth uint            download depth, 0 for unlimited (default 10)
  -x, --exclude stringArray   exclude URLs with PERL Regular Expressions support
  -h, --help                  help for goscrape
  -i, --imagequality int      image quality, 0 to disable reencoding
  -n, --include stringArray   only include URLs with PERL Regular Expressions support
  -o, --output string         output directory to write files to
  -t, --timeout uint          time limit in seconds for each http request to connect and read the request body
  -u, --user string           user[:password] to use for authentication
  -v, --verbose               verbose output
```
