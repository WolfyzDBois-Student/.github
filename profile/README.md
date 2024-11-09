```bash
wolfyzdbois:~$ cat description.cs
> You have just landed on my space reserved for studies.
> Public repo: Training, tests ...
> Repo on whitelist: Corrections & Documents reserved for those concerned
> Otherwise, this is a private storage space
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
           return(["Alias", "GitGuide", "TemplateLatex"]);
        }
    else throw new UnauthorizedAccessException("Hmmm...who are you?");
        
    }
}
