# annoying-kids-games
Block List of Annoying Kids Games

A PiHole block list to prevent access to popular gaming websites.

## Blocked Domains

This comprehensive list includes nearly 150 gaming website domains organized into categories:

### Popular Gaming Portals
- poki.com
- crazygames.com
- coolmathgames.com
- addictinggames.com
- miniclip.com
- agame.com
- y8.com
- kongregate.com
- newgrounds.com
- armorgames.com
- gamesfreak.net
- gamesgames.com
- kizi.com
- friv.com
- mousebreaker.com
- notdoppler.com
- silvergames.com
- lagged.com
- iogames.space
- girlsgogames.com

### Unblocked Games Sites
Sites specifically designed to bypass school/network filters:
- unblockedgames66.com
- unblockedgames77.com
- unblockedgames24h.com
- unblockedgames666.com
- unblockedgamespod.com
- unblockedgames76.io
- unblockedgames333.com
- hooda-math.com / hoodamath.com
- funblockedgames.com
- mills-eagles.com

### IO Games
Popular multiplayer browser games:
- agar.io
- slither.io
- diep.io
- surviv.io
- moomoo.io
- krunker.io
- skribbl.io
- shellshock.io
- zombs.io
- starve.io
- wings.io
- gats.io
- splix.io
- powerline.io
- hole.io
- wormate.io
- deeeep.io
- wilds.io
- paper-io.com

### Multiplayer Battle Royale and Action Games
- 1v1.lol
- ev.io
- venge.io
- shellshockers.com
- buildroyale.io
- zombsroyale.io

### Flash Game Archives
- bluemaxima.org
- flasharch.com
- flashgames247.com
- arcadeprehistoric.com

### Math and Educational Game Sites
Often used as "educational" covers for gaming:
- mathplayground.com
- funbrain.com
- coolmath.com
- coolmath4kids.com

### Puzzle and Casual Games
- puzzlegames.com
- freeonlinegames.com
- primarygames.com
- games.co.uk
- andkon.com

### Sports Games
- soccergames.io
- basketballlegends.io

### Other Popular Game Sites
- nitrome.com
- tinytap.com
- gamesbutler.com
- bigfishgames.com
- bgames.com
- maxgames.com
- twoplayergames.org
- playretrogames.com
- playclassic.games

### Google Sites
- sites.google.com (Warning: This may block legitimate Google Sites content)

**Note:** Both the base domain and www subdomain are blocked for each site to ensure comprehensive coverage.

## Usage with PiHole

1. Log in to your PiHole admin interface
2. Navigate to **Adlists** (under Group Management)
3. Add the following URL to your block lists:
   ```
   https://raw.githubusercontent.com/gerry421/annoying-kids-games/main/blocklist.txt
   ```
4. Click "Add"
5. Update Gravity: Go to **Tools** > **Update Gravity** and click "Update"

The domains in this list will now be blocked on your network.
