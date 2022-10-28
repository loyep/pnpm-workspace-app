# pnpm-app

执行

```bash
pnpm build
```

```bash
> pnpm --filter "@pnpm-app/*" build

Scope: 5 of 6 workspace projects
packages/a build$ echo "build a"
│ build a
└─ Done in 12ms
packages/c build$ echo "build c"
│ build c
└─ Done in 12ms
packages/e build$ echo "build e"
│ build e
└─ Done in 12ms
packages/b build$ echo "build b"
│ build b
└─ Done in 6ms
packages/d build$ echo "build d"
│ build d
└─ Done in 7ms
```
