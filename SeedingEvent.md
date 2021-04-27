Starting with a secret I've generated a chain of 1,000,000 SHA256 hashes. Each element is the hash of the lowercase, hexadecimal string representation of the previous hash. The hash of the chain's last element is 9816037b50aee38cd0ef6340cf7068906b21987b36ec11ce48f8fdee8e20a4b3.

Every game maps to a hash in the chain: The 1,000,000th element of the chain is the hash of game #1 and the first element in the chain is the hash of game #1,000,000. To verify that a hash belongs to a game #n, simply hash it n times and compare the result with the terminating hash.

You can view the current source code to calculate crash points here: https://jsfiddle.net/slamtoken/zawhq843/embedded/result/
Using this code, you will verify the the legitimacy of the game results.

To calculate crash points, we need a client seed string to hash each game.  So, this is a public announcement that the lowercase, hexadecimal string representation of the hash of BINANCE SMART CHAIN BLOCK 6938300. This block has not been mined yet, proving that I have not deliberately picked a chain that is unfavorable for players.

Countdown for block: https://bscscan.com/block/countdown/6938300
This message will be tweeted, posted on GitHub, Reddit and we will take screenshots to keep on web-archive for verification in the future.

For Github, you can check the timestamp of this file.
