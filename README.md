# dark-mode-sample

```
:root {
	  /* ベースの色（白色） */
	  --color-bg: #f9f9f9;
	  /* テキストの色（黒色） */
	  --color-text: #333333;
	}

	/* ダークモードの対応 */
	@media (prefers-color-scheme: dark) {
	  :root {
	    /* ベースの色（黒色） */
	    --color-bg: #333333;
	    /* テキストの色（白色） */
	    --color-text: #ffffff;
	  }
	}

	body {
	  /* CSS変数: 背景の色 */
	  background-color: var(--color-bg);
	  /* CSS変数：テキストの色 */
	  color: var(--color-text);
	}
```
