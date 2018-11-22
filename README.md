# wnoty
JQuery notify by WOLK

Demo:
https://wolkkr.github.io/wnotydemo/

![alt text](https://image.prntscr.com/image/_7qThaddQHyX6_9bF-pIsA.png)

### Usage

4 type `success`, `error`, `warning` and `info`

```sh
$.wnoty({
	type: 'error',
	message: 'message'
});
```

### Options

| Option | Value |
| ------ | ------ |
| position | "top-left", "bottom-left", "top-right", "bottom-right" |
| types | "error", "success", "warning", "info" |
| autohide | true\false |
| autohideDelay | 2500 (default) |
