# IPInfo.cs
Web-API for [ipinfo.io](https://ipinfo.io) an accurate IP address data that keeps pace with secure, specific, and forward-looking use cases

## Example
```cs
using IPInfoApi;

namespace Application
{
    internal class Program
    {
        static async Task Main()
        {
            var api = new IPInfo();
            string ipInfo = await api.GetIpInfo("192.168.1.1");
            Console.WriteLine(ipInfo);
        }
    }
}
```
