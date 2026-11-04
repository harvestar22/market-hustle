# Market Hustle post queue

The MH Bot pulls scheduled Instagram/TikTok posts from this branch (`queue.json` lists each post folder with checksums).
Each folder holds `post.json` (kind, title, date, time in Toronto time), `caption.txt` and the media.
This branch doesn't affect the website, which is served from `main`.
