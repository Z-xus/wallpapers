# Zenful Wallpaper Collection

![Img](./new/bg.png)
![Img](./new/chill.gif)

## Optimizing Git for Large Repositories

If you experience slow network speeds while cloning this repository, consider using the following Git configurations to improve download performance:

```bash
# Increase the HTTP post buffer size to handle large files
git config --global http.postBuffer 524288000

# Disable the low speed limit to prevent timeout issues
git config --global http.lowSpeedLimit 0

# Increase the low speed time to give the download process more time to complete
git config --global http.lowSpeedTime 999999
