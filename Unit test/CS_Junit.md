# TDD with Junit

* [Last Update and news](https://junit.org/)
* [More Method here ( junit4 )](https://junit.org/junit4/javadoc/4.8/org/junit/Assert.html)

```
import org.junit.Assert;
import org.junit.Test;

public class ClassNameTest {

    @Test
    public void testTrue() throws Exception {
        Assert.assertEquals(true, true);
    }

    @Test
    public void ClassNameTestTrue() throws Exception {
        Assert.assertEquals(0, ClassName.methods(0));
    }
}
```