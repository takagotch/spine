### spine
---
https://github.com/spine/spine

```js
// test/controler.js
describe("Controller", function() {
  var Users;
  var elements;
  
  beforeEach(function() {
    Users = Spine.Controller.sub();
    element = ${"<div />"};
  });
  
  it("should be configurable", function() {
    element.addClass("testy");
    var users = new Users({el: element});
    expect(users.el.hasClass("testy")).toBeTruthy();
    
    users = new Users({item: "foo"});
    expect(users.item).toEqual("foo");
  });
  
  
  
  
});

```

```
```

```
```

