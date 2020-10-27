# cartwise

puts the instacart receipt into splitwise, itemized

TODO
- [ ] Parse the instacart receipt into a 2 array of [[name, price], ...]
- [ ] request from splitwise the names of those in the group
- [ ] post to splitwise a request to setup this itemised expense
- [ ] profit




```
cost: 5
currency_code: USD
group_id: 21391998
users__0__user_id: 4348166
users__0__paid_share: 5.00
users__0__owed_share: 3.50
users__1__user_id: 36079180
users__1__paid_share: 0.00
users__1__owed_share: 1.50
category_id: 18
id: 1110907095
description: test
repeats: false
repeat_interval: never
email_reminder: false
email_reminder_in_advance: -1
payment: false
creation_method: equal
transaction_method: offline
date: 2020-10-27T05:26:58Z
details: this - 3.00 (R2 Hughes, Rory Hughes)
that - 2.00 (Rory Hughes)
Tax: R2 Hughes - 0.00, Rory Hughes - 0.00
Tip: R2 Hughes - 0.00, Rory Hughes - 0.00
```

## Notes

This example shows how to integrate the TypeScript type system into Next.js. Since TypeScript is supported out of the box with Next.js, all we have to do is to install TypeScript.

```
npm install --save-dev typescript
```

To enable TypeScript's features, we install the type declarations for React and Node.

```
npm install --save-dev @types/react @types/react-dom @types/node
```

When we run `next dev` the next time, Next.js will start looking for any `.ts` or `.tsx` files in our project and builds it. It even automatically creates a `tsconfig.json` file for our project with the recommended settings.

Next.js has built-in TypeScript declarations, so we'll get autocompletion for Next.js' modules straight away.

A `type-check` script is also added to `package.json`, which runs TypeScript's `tsc` CLI in `noEmit` mode to run type-checking separately. You can then include this, for example, in your `test` scripts.
