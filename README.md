# How does one do this dumb thing

- `svnadmin create foo`
- `svn import wherever/empty file:///wherever/foo`
- `cd foo`
- `git add .svn`
- `git commit`
- `svn add .git`
- `svn commit`

# Why?

I dunno, why not :shrug:
