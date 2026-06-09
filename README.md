# WalidDevs / README.md

<div align="center">
  <a href="https://walidelalami.com">
    <img src="https://img.shields.io/badge/Portfolio-walidelalami.com-002248?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
  <a href="https://github.com/WalidDevs">
    <img src="https://img.shields.io/badge/GitHub-WalidDevs-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/walid-elalami-8195a5214/">
    <img src="https://img.shields.io/badge/LinkedIn-Walid%20ELALAMI-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</div>

---

```csharp
namespace AboutMe
{
    public class Person
    {
        public string Name { get; } = "Walid ELALAMI";
        public string Aka { get; } = "WalidDevs";
        public string Location { get; } = "Paris, France";

        public List<string> MainStack { get; } = new()
        {
            "C#",
            ".NET Core",
            "React",
            "TypeScript"
        };

        public List<string> Interests { get; } = new()
        {
            "Clean Architecture",
            "REST APIs",
            "Software Design",
            "Full-Stack Development"
        };

        public string Goal { get; } =
            "Building clean, scalable and secure web applications.";
    }
}
