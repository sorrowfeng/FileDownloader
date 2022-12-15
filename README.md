# FileDownloader
简易的Qt文件下载器

# 使用示例
```cpp
    FileDownloader *mFileDownloader = new FileDownloader(url, this);
    connect(mFileDownloader, &FileDownloader::downloaded,[=]() {        
        mFileDownloader->downloadedData();
    }
```