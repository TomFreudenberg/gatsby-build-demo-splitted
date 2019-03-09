# Steps how the demo was created

``` bash
mkdir build-demo
cd build-demo

npx gatsby new pdf_docs https://github.com/gatsbyjs/gatsby-starter-hello-world
npx gatsby new pdf_app https://github.com/gatsbyjs/gatsby-starter-hello-world
```

# Steps to reproduce the demo from repository

``` bash
git clone build-demo
cd build-demo
```

### first create the pdf_document(s)

``` bash
cd pdf_docs
npm install
npm run build
npm run build_pdfs
```

### second create the client app

``` bash
cd ../pdf_app
npm install
npm run build
npm run serve
```

Now it is possible to get the PDF from http://localhost:9000/

# Question

## How to meld all in one project and one build process?
