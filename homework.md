we will use parcel as the bundler in our project.

package-lock json keeps the note of exact version of the package/dependency.

diff between ~ and ^.
^ (Caret):Allows updates to minor and patch versions.
~ (Tilde):Allows updates to patch versions only.

remember you removed main:app.js from package.json

npx is used to execute a package
npm is used to install a package

WHAT DOES PARCEL DO?
~local server
~dev build
~hmr->hot module replacement->automatically refresh the ~page and server
~uses a file watching algo->C++
~also caches things for us
~image optimization
~code splitting
~continuous hashing
