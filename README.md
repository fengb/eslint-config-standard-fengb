# eslint-config-standard-fengb

[JavaScript Standard Style](http://standardjs.com/) with minor modifications.

Looking for the actual Standard? Try https://github.com/feross/standard or https://github.com/feross/eslint-config-standard

## Why fork Standard?

I agree with a lot of Standard and can tolerate most of the rest, but a few
things bother me. Here are my reasons for the differences:

#### `"comma-dangle": [2, "always-multiline"]`

This is nice for consistency. Otherwise, deleting lines can cause annoying
syntax juggling or diffs.

#### `"no-multi-spaces": 0`

I sometimes use multiple spaces to line up elements in an array (a la fake
matrix). I may revisit this since I usually dislike multi-spaces.

#### `"key-spacing": [2, { "beforeColon": false, "afterColon": true, "mode": "minimum" }]`

Sometimes I like to align values pairs, but sometimes I don't. I might change
this to `"align": "value"` though...
