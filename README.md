```bash
wolfyzdbois:~$ cat description.cs
> You have just landed on my space reserved for studies.
> This space includes my personal projects, my training, my tests ...
> This space is private.
> Some repositories will be public (some tests and training), others reserved on whitelist for students concerned by this space.
```


```cs

using WolfyzDBois;

class Program
{
    static void Main()
    {
        
    if (userInput == "student" && know == true)
    {
       return("WolfyzDBois in DM on Discord to access the repositories that interest you");

    }
    else if (userInput == "student" && know == false)
        {
           return("No repositories are public to date...");
        }
    else throw new UnauthorizedAccessException("Hmmm...who are you?");
        
    }
}
