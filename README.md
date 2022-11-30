package Learnings;

import org.testng.Assert;
import org.testng.annotations.*;

public class demo {

    @BeforeMethod
    public void beforeMethod()
    {
        System.out.println("Before Method");

    }

    @BeforeClass
    public void beforeClass ()
    {
        System.out.println("Before Class");
    }


    @AfterMethod
    public void AfterMethod () {
        System.out.println("After Method");
    }
    @AfterClass
    public void afterClass ()

    {
        System.out.println("After Class");
    }
    @Test
    public void firstTest()
    {
        System.out.println("First Test");
        Assert.assertEquals(1,2);

    }
    @Test
    public void secondTest()
    {
        System.out.println("Second Test");
    }
    @Test
    public void thirdTest()
    {
        System.out.println("Third Test");
    }
    @Test
    public void fourthTest()
    {
        System.out.println("Fourth Test");
    }
}



