const { Moddio } = require('moddio/server');

const moddio = new Moddio({
  appId: 'app_cf9610a5099e799dbb8919b7',
  appSecret: 'sk_live_ffe6a345c45b8071a6a8cd2f089d787e1741965243266071',
});

moddio.on('playerJoin', (player) => {
  console.log(player.id);          // unique player ID
  console.log(player.name);        // display name
  console.log(player.data);        // saved game data (guaranteed loaded)
  console.log(player.permissions); // { chat: true, vip: false }
});

// Save player data anytime
moddio.savePlayerData(player.id, { highScore: 9001 });
