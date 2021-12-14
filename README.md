# Alto-lite

Fork of [Alto](https://github.com/TryGhost/Alto) theme for a personal blog.

Key differences and features:

- removed featured post, pictures in the post feed, etc
- removed author of a post (for personal blog it is useless)
- dark reader support
- fix github actions deploy script (added "yarn build" step)
- decrease distanse between header and excerpt in the posts feed (margin-bottom reduced to 10px)
- Except posts with "translation" tag from main page feed (it shown on other page)

## Usage

1. Fork
2. Fill Settings > Secrets > "Repository secrets" with 2 keys: 
    - `GHOST_ADMIN_API_URL`
    - `GHOST_ADMIN_API_KEY` 

    For more information see [TryGhost/action-deploy-theme](https://github.com/TryGhost/action-deploy-theme).
    
3. Enjoy! :)
