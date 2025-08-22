<h1>
    <img src="worldguard-logo.svg" alt="WorldGuard" width="400" /> 
</h1>

Implements per-world event whitelisting as seen in
the `config.yml`. Check it out for more information!

How to deactivate unused events:
```yml
events:
    whitelist-mode: false
    disabled: ["PlayerInteractEvent"]
```

Functionally, you can toggle `whitelist-mode` to disable all events; except those in `events.disabled`.


Compiling
---------

See [COMPILING.md](COMPILING.md).

Contributing
------------

We happily accept contributions, especially through pull requests on GitHub.

Please read CONTRIBUTING.md for important guidelines to follow.

Submissions must be licensed under the GNU Lesser General Public License v3.