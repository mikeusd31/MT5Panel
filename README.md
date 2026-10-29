# MT5 Panel

**English** | [Türkçe](README.tr.md)

A portable trading panel for MetaTrader 5 on Windows: one-click trading, charting tools, an SL manager, a hedge module and an AI assistant. It installs into your user folder and needs no administrator rights. The interface is available in English and Turkish.

> ⚠️ **Risk warning:** Trading Forex and CFDs carries a high level of risk and you can lose all of your capital. This software does not provide investment advice and does not guarantee profits. **Try it on a demo account first.** The software is provided "as is" and the developer is not liable for any losses resulting from its use.

## Download

**[➡ Download the latest release](https://github.com/YOUR_USERNAME/MT5Panel/releases/latest)**

| File | What it is |
|---|---|
| `MT5Panel-Setup-x.y.z.exe` | Installer (installs into your user folder, no administrator rights needed) |

**Verify your download.** Every release page lists the SHA256 hash of each file. On Windows, run:

```
certutil -hashfile MT5Panel-Setup-x.y.z.exe SHA256
```

The output must match the value on the release page exactly.

> Windows SmartScreen may show "Windows protected your PC" because the program is not code-signed yet. Click **More info → Run anyway** to continue, after checking the SHA256 hash as shown above.

## Requirements

- Windows 10 / 11 (64-bit)
- An MT5 trading account (account number, server, password). **A demo account is recommended at first.**
- Internet connection

## First run

1. Open the program, enter your **account number**, **server** and **password**, then click **Login**.
2. Your password is stored only on your own computer, encrypted with Windows' per-user protection, and only if "Save password" is ticked.
3. The language is changed from the list at the top of the window (restart required).

## Features

**Base features (free):** login with your MT5 account, one-click Buy/Sell (lot +/−, SL/TP), position list and bulk close, Market Watch (spread and daily change), candlestick chart, MA20/50/200 and Bollinger Bands, drawing tools (trend line, horizontal/vertical line, rectangle, measuring tool), screenshots, full-screen mode, and an economic calendar (high-impact events).

**Licensed features** (require a license file):

| Feature | Description |
|---|---|
| SupDem | Supply / Demand zones |
| Grid Level | Price levels around the H1 open, with the step set in USD or pips |
| Swing lines | Untested swing high / low lines with a sound alarm when price approaches |
| Session boxes | Asia, London and New York ranges |
| Hedge | Hedge with scale-out closing, hourly automatic hedge |
| SL Manager | Common stop-loss calculated from your risk |
| AI assistant | Chart analysis with Claude / ChatGPT / Gemini (your own API key or credits) |
| Multi-chart | Up to 8 charts in tabs |
| Fibo | Fibonacci drawing tool |

## How to get a license

1. In the program, click the **License** button and copy your **computer ID**.
2. Send it to me: `mikeeur31@gmail.com`
3. I will send you a `license.lic` file. Put it in the program folder, or choose it with **License → Load license file...**

Do not share your license file; it may be bound to your computer and/or your account. Without a license the program keeps working with the base features.

## Reporting problems

Open an issue in the [Issues](https://github.com/YOUR_USERNAME/MT5Panel/issues) section. **Before posting**, remove or blur your account number, balance and any password from screenshots and logs.

## Privacy

- Trades are sent directly between your MT5 account and your broker's server. Your account details are not sent to me.
- When you use the AI assistant, chart data is sent to the provider you choose (Claude / OpenAI / Gemini).

## Terms of use

See [EULA.txt](EULA.txt).
