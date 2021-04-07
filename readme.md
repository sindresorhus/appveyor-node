Unmaintained. Just use GitHub Actions. It is better in every way.

---

# appveyor-node

> Boilerplate [`appveyor.yml`](http://www.appveyor.com/docs/appveyor-yml) file for running Node.js tests on [AppVeyor](http://www.appveyor.com)

Because it's so much harder than it should be...

## Usage

- Go to the AppVeyor website and [add the repo](https://ci.appveyor.com/projects/new) you want to test.

- Fetch the `appveyor.yml` file directly:

	```
	$ curl -fsSLO https://github.com/sindresorhus/appveyor-node/raw/main/appveyor.yml
	```

	Or [download it](https://github.com/sindresorhus/appveyor-node/raw/main/appveyor.yml) manually. *(Right-click and choose "Save link as...")*

- Add the badge to your readme. You can get it here:

	```
	https://ci.appveyor.com/project/{user}/{repo}/settings/badges
	```

	*Replace `{user}` and `{repo}` with your GitHub username and repo.*

- Commit and push.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
