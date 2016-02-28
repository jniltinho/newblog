# newblog
New Blog LinuxPro with Hugo Golang



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