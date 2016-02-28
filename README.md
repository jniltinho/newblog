# Create your Blog with Hugo Golang
[Youtube Channel LinuxPro](https://www.youtube.com/c/LinuxPro-Screencast)



# Install Hugo 0.15 on Linux 64Bits

```bash
cd /tmp/
wget --no-check-certificate https://github.com/spf13/hugo/releases/download/v0.15/hugo_0.15_linux_amd64.tar.gz
tar -xzf hugo_0.15_linux_amd64.tar.gz
sudo cp hugo_0.15_linux_amd64/hugo_0.15_linux_amd64 /usr/local/bin/hugo
rm -rf hugo_0.15_linux_amd64*
hugo version
```


# Create Blog

```bash
git clone https://github.com/jniltinho/newblog
cd newblog
hugo server --buildDrafts
# Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
```


# Links
- https://gohugo.io/overview/installing/
- https://gohugo.io/overview/quickstart/
- https://github.com/spf13/hugo/releases
- https://github.com/spf13/hugo
- [hugo-a-static-site-generator](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-hugo-a-static-site-generator-on-ubuntu-14-04)
- [Site LinuxPro](www.linuxpro.com.br)
- [Old Blog LinuxPro](http://blog.linuxpro.com.br)