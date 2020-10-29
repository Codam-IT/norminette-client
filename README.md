<h1 align="center"><code>Norminette</code></h1>

---

# Norminette

Check that the source code respects the school’s norm.

# Installing instructions

### OSX:

```bash
git clone https://github.com/codam-coding-college/norminette-client.git ~/.norminette/
cd ~/.norminette/
bundle 
```

**Create a symbolic link**

```bash
sudo ln -s ~/.norminette/norminette.rb /usr/local/bin/norminette
```

<br /><br />
### GNU/Linux

```bash
sudo apt-get install ruby ruby-bundler ruby-dev build-essential
git clone https://github.com/codam-coding-college/norminette-client.git ~/.norminette/
cd ~/.norminette/
bundle
```

**Create a symbolic link**

```bash
sudo ln -s ~/.norminette/norminette.rb /usr/local/bin/norminette
```


### FAQ

**Symbolic link already exist, what can i do ?**

failed to create symbolic link '/usr/local/bin/norminette': File exists **

```bash
sudo unlink /usr/local/bin/norminette
sudo ln -s ~/.norminette/norminette.rb /usr/local/bin/norminette
```





