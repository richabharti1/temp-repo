# WebScrapper Extension

Uses [chrome-extension-boilerplate-react](https://github.com/lxieyang/chrome-extension-boilerplate-react) boilerplate.

## Installing and Running

### Development:

1. Check if your [Node.js](https://nodejs.org/) version is >= **14**.
2. Run `npm install` to install the dependencies.
3. Run `npm start`
4. Load your extension on Chrome following:
    1. Access `chrome://extensions/`
    2. Check `Developer mode`
    3. Click on `Load unpacked extension`
    4. Select the `build` folder.

### Production build:

1. Stop development script (if it is running)
2. Remove installed dev. extension at `chrome://extensions/`
3. Run `npm run build`
4. Load your extension on Chrome following:
    1. Access `chrome://extensions/`
    2. Check `Developer mode`
    3. Click on `Load unpacked extension`
    4. Select the `build` folder

## API links

Swagger - https://clipper-backend-demo.herokuapp.com/api/swagger/

https://clipper-backend-demo.herokuapp.com/api/redoc/

Admin panel - https://clipper-backend-demo.herokuapp.com/admin/clipper/webclip/
