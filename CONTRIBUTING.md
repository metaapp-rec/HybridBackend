# How to contribute

We appreciate all contributions to improve HybridBackend. You can create an
[issue](https://github.com/alibaba/HybridBackend/issues) or send a
[pull request](https://github.com/alibaba/HybridBackend/pulls).

**Working on your first Pull Request?** You can learn how from this *free*
series [How to Contribute to an Open Source Project on GitHub](https://kcd.im/pull-request)

## Code style

Before any commits, please use below tools to format and check code style:

```bash
build/run tools/format
build/run tools/lint
```

Commit message style should follow below format:

```text
[Module] Do something great.
```

`Module` could be `CI`, `IO` or other well-known abbreviations.

## Building and testing

Test your commit using default developer docker:

```bash
build/run make -j8
build/run make test
```

Also, CI builds would be triggered if a commit is pushed.
