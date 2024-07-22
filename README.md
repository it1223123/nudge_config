use `log stream --predicate 'subsystem == "com.github.macadmins.Nudge"' --style ndjson --color none | egrep --line-buffered '^{' | jq '. | .eventMessage'` to keep an eye on a test machine/s
