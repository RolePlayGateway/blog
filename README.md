RPG Blog
======
Source code for RolePlayGateway's Blog.

## Quick Start
You'll want to get your own fork of this repository by clicking "fork" in the
top right hand corner.  Once complete, setup should be as follows:

```bash
git clone git@github.com:YOUR_USERNAME/blog.git blog.roleplaygateway.com
cd blog.roleplaygateway.com
git remote add upstream git@github.com:RolePlayGateway/blog.git
```

Now, install all the dependencies:

```bash
npm install
```

Run a copy of the blog locally, but be on the lookout for a password: you'll
only see it once!

```bash
node rpg\:blog.js
```

You might want a tool like `nodemon` to automatically restart the blog if you
make changes to the internals: `npm install nodemon -g` – running the blog this
way is very simple, just replace `node` with `nodemon`, resulting in:

```
nodemon rpg\:blog.js
```
