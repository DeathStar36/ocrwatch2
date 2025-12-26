# OCRWatch

Using OCR to track match stats & team performance in Overwatch 2  
Fancier continuation of https://github.com/InventivetalentDev/ocrwatch

## How it works
While this app is running, it listens for key presses of the configured hotkey (default: Tab) and takes a screenshot of the scoreboard if it's held for more than 0.5 seconds.
It then applies OCR on that screen, including mode and map info, which hero you're playing and stats of you and other players in your game (kills, deaths, healing, etc.) and saves that data.

## Configuration
Edit `config.json` to change settings:
- `hotkey`: The key to listen for (e.g., "Tab", "Space", "F1"). Use the key name as defined in UiohookKey enum.



## Usage
```
git clone https://github.com/InventivetalentDev/ocrwatch2.git
cd ocrwatch2
```
```
npm install
npm run start
```


![](https://yeleha.co/8uD3zIdt)
