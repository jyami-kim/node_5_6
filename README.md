# node_study
노드 공부

Express 서버가 3000번 포트에서 시작됨
/process/photo 호출됨
'#==================업로드된 파일 정보===================#'
'TypeError: Cannot read property \'0\' of undefined\n    at C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\practice.js:84:30\n    at Layer.handle [as handle_request] (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\layer.js:95:5)\n    at next (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\route.js:137:13)\n    at multerMiddleware (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\multer\\lib\\make-middleware.js:18:41)\n    at Layer.handle [as handle_request] (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\layer.js:95:5)\n    at next (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\route.js:137:13)\n    at Route.dispatch (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\route.js:112:3)\n    at Layer.handle [as handle_request] (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\layer.js:95:5)\n    at C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\index.js:281:22\n    at Function.process_params (C:\\Users\\mor22\\Desktop\\ExpressExample\\myExpressApp\\node_modules\\express\\lib\\router\\index.js:335:12)'

파일업로드를 시도했으나, 해당 에러가 떴다. => multipart파일 처리가 잘 안된건지 잘 모르겠다.
