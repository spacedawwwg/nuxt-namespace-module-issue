# nuxt-namespace-module-issue

Cannot import scoped/namespaced packages into Nuxt vue components, e.g:

`import { HelloWorld } from '@testname/package-a/lib'`

instead having to resort to

`import { HelloWorld } from '~/node_modules/@testname/package-a/lib'`

Issue seems to be with the use of `@` in the scope/namespace
