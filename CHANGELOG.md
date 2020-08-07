# v1.5.2 (Fri Aug 07 2020)

### Release Notes

_From #11_

### This is some markdoooown

```jsx
<Button color="magenta">Magenta!</Button>
```

---

#### 🐛 Bug Fix

- Slack all day [#11](https://github.com/goldenshun/auto-demo/pull/11) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# (Fri Aug 07 2020)

### Release Notes

_From #10_

Just updating config

---

#### ⚠️ Pushed to `master`

- Try slack integration ([@goldenshun](https://github.com/goldenshun))

#### 📝 Documentation

- Custom labels [#10](https://github.com/goldenshun/auto-demo/pull/10) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# v1.5.0 (Fri Aug 07 2020)

### Release Notes

_From #8_

### Cool stuff happened
```
console.log('auto-demo for lisa');
```

Oh yeah and I forgot we need to add this very important note.

---

#### 🚀 Enhancement

- Demo for Lisa [#8](https://github.com/goldenshun/auto-demo/pull/8) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# v1.4.0 (Fri Aug 07 2020)

### Release Notes

_From #7_

Use `.autorc` instead of polluting `package.json` with more stuff.

---

#### 🚀 Enhancement

- Use autorc instead [#7](https://github.com/goldenshun/auto-demo/pull/7) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# v1.3.0 (Fri Aug 07 2020)

### Release Notes

_From #6_

```yml
pr_check:
    <<: *defaults
    steps:
      - checkout
      - run: npx auto pr-check --url ${CIRCLE_BUILD_URL}

- pr_check:
          filters:
            branches:
              ignore:
                - master
```

_From #4_

Adding a PR check:
```yml
jobs:
  release:
    <<: *defaults
    steps:
      - checkout
      - run: npm ci
      - run: npx auto pr-check --url ${CIRCLE_BUILD_URL}
      - run: npx auto shipit
```

---

#### 🚀 Enhancement

- Add pr check [#4](https://github.com/goldenshun/auto-demo/pull/4) ([@goldenshun](https://github.com/goldenshun))

#### 🐛 Bug Fix

- Move PR check back to separate job [#6](https://github.com/goldenshun/auto-demo/pull/6) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# v1.2.1 (Fri Aug 07 2020)

### Release Notes

_From #3_

Making a very meaningful change here:
```
console.log('auto-demo 6 pr-3');
```

---

#### 🐛 Bug Fix

- Going with PR 3 [#3](https://github.com/goldenshun/auto-demo/pull/3) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# v1.2.0 (Fri Aug 07 2020)

#### 🚀 Enhancement

- Trying PR 2 [#2](https://github.com/goldenshun/auto-demo/pull/2) ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))

---

# v1.1.0 (Fri Aug 07 2020)

#### 🚀 Enhancement

- Try a PR [#1](https://github.com/goldenshun/auto-demo/pull/1) ([@goldenshun](https://github.com/goldenshun))

#### ⚠️ Pushed to `master`

- Take 3 ([@goldenshun](https://github.com/goldenshun))
- Take 2 ([@goldenshun](https://github.com/goldenshun))

#### Authors: 1

- Sean Connolly ([@goldenshun](https://github.com/goldenshun))
