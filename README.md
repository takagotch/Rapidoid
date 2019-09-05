### rapidoid
---
https://github.com/rapidoid/rapidoid

https://www.rapidoid.org/

```java
// rapidoid-render/src/test/java/org/rapidoid/render/MultiTemplateRenderTest.java

@Author("Nikolche Mihajlovski")
@Since("5.1.0")
public class MultiTemplateRenderTest extends TestCommons {

  @Test
  public void testTemplateLoading() {
    Template temp1 = Templates.load("templ1.html");
    
    eq(templ.render(U.map("x", "123")), "A:123:B:OK:C");
  }
}
```

```
```

```
```


