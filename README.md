# my100devs
A repo dedicated to my efforts and contributions to #100devs.

## Notes

### Installation
```bash
npm i express cors
```

### Solving CORS issue: 
If users want to run this from a client locally on their machine, this will not work as it only works serverside. USe the CORS package, require in server.js and run using `app.use(cors())`.