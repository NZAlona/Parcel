# Parcel Set up guidance

1. Make sure Node.js is installed (LTS - version)
2. Create repository and clone it
3. Check Parcel documentation https://parceljs.org/getting-started/webapp/#installation and install Parcel (npm install --save-dev parcel)
4. Create package.json file via npm init
5. Adjust scripts - entry points:
   start - parcel index.html or multiple _.html
   build - parcel build index.html or _.html
6. Install plugin (PostHtml include) to be able to add parcials but remain index.html as an entry point (npm i -D posthtml-include ). Afterwards create file .posthtmlrc and copy script from Parcel website
7. npm run start command opens Parcel development server
   Production
8. on GitHub in Action tab in section Workflow permissions - choose Read and Write perm; and Aloow GitHub accept pull requests
9. in file package.json in scrips need to add build-dev and push-gh-pages
10. for Windows users need to install plugin npm install push-dir
11. When it is time to deploy app use npm run push-gh-pages
