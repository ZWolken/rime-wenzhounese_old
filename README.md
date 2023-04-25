# 吳語·溫州話

[Rime](https://rime.im) 吳語-溫州話輸入方案

詞典根據[pearapple123/rime-iuciou](https://github.com/pearapple123/rime-iuciou)進行客制化

原拼寫方案參考：
1. [吳語學堂](https://wugniu.com/search?char=%E6%88%91&table=wenzhou)
2. [吳語協會](http://wu-chinese.com/romanization/wenzhou.html)
3. 溫州方言詞典 作者：李榮

客制化内容主要為模糊音，即`iuciou.custom.yaml`文件。

**注意：模糊音方案規則非常不嚴謹，有吳語拼寫經驗的不建議安裝模糊音(`iuciou.custom.yaml文件`)**

## 安裝

1. 安裝[Rime](https://rime.im)

2. 將`iuciou.schema.yaml`、`iuciou.dict.yaml`以及`iuciou.custom.yaml`（選擇性）三個文件放入用戶資料夾内
> 相關路徑：
>
> 【中州韻】 `~/.config/ibus/rime/` （0.9.1 以下版本爲 `~/.ibus/rime/`；fcitx5 为 `~/.local/share/fcitx5/rime/`）
>
> 【小狼毫】 `%APPDATA%\Rime`
>
> 【鼠鬚管】 `~/Library/Rime/`