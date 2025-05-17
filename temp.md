❌ Bad Code:
```javascript
function sum(){return a+b ;}
```

🔍 Issues:
* ❌ Missing parameters: The function `sum` is intended to add two numbers, but it doesn't define any parameters to
accept those numbers. As a result, it relies on variables `a` and `b` defined in the outer scope, which is not a good
practice.

✅ Recommended Fix:

```javascript
function sum(a, b) {
return a + b;
}
```

💡 Improvements:

* ✔️ Parameters added: The function now accepts two parameters, `a` and `b`, which makes it clear that it's intended to
add these two values.
* ✔️ Proper scope: The function now uses its own parameters instead of relying on variables from the outer scope, which
makes it more self-contained and less prone to errors.