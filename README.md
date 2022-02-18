# actions-sandbox

```
      - name: Run a one-line script
        run: echo "${{ github.ref }}"
```
のとき
```
Run echo "refs/heads/main"
  echo "refs/heads/main"
  shell: /usr/bin/bash -e {0}
refs/heads/main
```
