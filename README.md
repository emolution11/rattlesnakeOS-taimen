A custom shell script that sets a custom boot animation. You can test this out by adding the following to your rattlesnakeos-stack config file. See the [FAQ](https://github.com/dan-v/rattlesnakeos-stack#faq) for more details on customizations.

```
[[custom-scripts]]
  repo = "https://github.com/emolution11/script-custom-boot/"
  script-BA = ["custom-boot-animation.sh"]
```
