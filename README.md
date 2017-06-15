# mxsend - Matrix pipe sender

## Usage

```
sudo pip3 install -e git+https://github.com/matrix-org/matrix-python-sdk.git#egg=matrix-client
cp mxsend.conf ~/.config/mxsend.conf # and customize it with your creds
cp mxsend /usr/local/bin/mxsend # or somewhere else in your PATH
echo "this is a test message!" | mxsend test # if you have a room named "test" in your config
```
