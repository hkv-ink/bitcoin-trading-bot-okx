# MountAlpha 阿尔法峰 比特币自动交易软件（欧易版）

**MountAlpha OKX Edition** 是面向 OKX 欧易 USDT 永续合约的 Windows 中文客户端，包含模拟账户、独立实盘控制、持仓与订单记录，以及加密客服和文件传输。

## Windows 下载

[下载 MountAlpha-OKX-Setup.exe](https://github.com/hkv-ink/bitcoin-trading-bot-okx/releases/latest/download/MountAlpha-OKX-Setup.exe)。版本记录和 `SHA256SUMS.txt` 在[最新发行页](https://github.com/hkv-ink/bitcoin-trading-bot-okx/releases/latest)。这里是欧易中文版。币安英文版见 [MountAlpha Binance Edition](https://github.com/hkv-ink/bitcoin-trading-bot-binance)。

## 安装和首次运行

1. 使用 64 位 Windows 和 Microsoft Edge WebView2。安装前在 PowerShell 中核对 SHA-256，确认与 `SHA256SUMS.txt` 一致：
   ```powershell
   Get-FileHash -Algorithm SHA256 .\MountAlpha-OKX-Setup.exe
   ```
2. 打开「OKX 策略运行器 文件传输版」。建议先运行模拟账户；模拟不需要 OKX API 密钥。
3. 实盘默认暂停，需绑定所选账户、完成设备授权，并由用户手动启动。正常升级应在安全维护窗口直接覆盖原目录，不要先卸载，以免清除本地账本和 API 设置。

## 常见问题

**支持币安或现货吗？** 这个版本面向 OKX 欧易 USDT 永续合约。币安使用独立英文版，两边的设置、授权和账户数据不通用。

**下载包里有账户数据吗？** 不包含使用者的 API 密钥或交易账本。请勿在 GitHub Issues 或客服聊天中发送密钥、密码或验证码。

**历史回测或模拟结果能代表实盘收益吗？** 不能。杠杆交易可能造成重大损失，模拟不等于实际成交。使用前请确认所在地区许可本软件相关用途和交易产品。MountAlpha 不是 OKX 欧易官方产品。

## 联系支持

使用软件内「联系客服」功能。说明客户端版本和问题现象，并遮挡账号、设备标识、授权码和任何密钥。

开源客服组件的[对应源码、构建说明和许可证](https://github.com/hkv-ink/bitcoin-trading-bot-okx/releases/latest/download/MountAlpha-OKX-Support-Source.zip)作为独立附件提供。随包的 SimpleX 原生库与 [v7.0.3 上游源码](https://github.com/simplex-chat/simplex-chat/tree/v7.0.3)对应。附件不包含私有交易策略。
