<pre> ```csharp // using System;
using System.Collections.Generic;

public static class Me
{
    public static readonly string[] ABOUT = new string[]
    {
        "大号被一个笨蛋丢了，这是第二个号"
    };

    public static readonly string[] Learning = new string[]
    {
        "Unity / CSharp",
    };

    public static readonly string[] DEVICES = new string[]
    {
        "Redmi Note 12 Turbo / POCO F5"
    };

    public static Dictionary<string, string> Contact()
    {
        return new Dictionary<string, string>
        {
            { "Email", "CnBarrier0921@outlook.com" },
            { "Telegram", "https://t.me/CnBarrier" }
        };
    }
}
 ``` </pre>
