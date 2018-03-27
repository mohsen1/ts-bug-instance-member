# ts-bug-instance-member

Bug:

`Ex` is not defining `foo` as instance member

```
 yarn test
yarn run v1.3.2
$ tsc --pretty
index.js:7:19 - error TS2424: Class 'Ex' defines instance member function 'foo', but extended class 'MyClass' defines it as instance member property.

7 MyClass.prototype.foo = function() {
                    ~~~

```
