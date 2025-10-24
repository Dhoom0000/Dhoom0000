```md
# Hello World!
```

```rust
#[derive(He, Him)]
struct Me;

const NAME: &str = "Dhrumil Shah";

/// Contact Me! Looking for jobs!
const LOCATION: &str = "Cambridge, UK";
const EMAIL: &str = "dhrumilshah.exc@outlook.com";
const LINKEDIN: &str = "https://www.linkedin.com/in/dhrumil-shah-bssl";
```

```rust
impl About for Me {

    fn summary() {
        let summary = "\
        I am a computer science student focused on practical \
        software solutions across Embedded Systems, Machine Learning \
        Game Development, and Cybersecurity. I use Rust primarily and \
        aim to expand technical skills while delivering reliable, \
        efficient, and maintainable code.
        ";
    }

    fn education() {
        // Bachelor's Degree
        let bachelors_degree = "B.Eng. (Hons) Computer Science";
        let b_institution = "Anglia Ruskin University, Cmabridge";
        let b_year_of_attendance = "2023 - 2026";

        // Master's Degree
        let masters_degree = "M.Sc. Cyber Security";
        let m_institution = "Anglia Ruskin University, Cambridge";
        let m_year_of_attendance = "2026-2027";
    }

    fn skills() {
        let programming = vec!["C", "C++", "Java", "Python", "Rust", "MATLAB", "SQL"];

        let tools = vec!["Git", "GitHub", "Linux", "AWS", "Docker", "Figma", "Bevy ECS"];

        let methodologies = vec!["Debugging", "UI/UX", "Accessibility", "Agile", "Prototyping", "Object-Oriented"];

        let languages = vec![(English, Fluent), (Hindi, Fluent), (Gujarati, Fluent), (German, Beginner)];
        // FIXME: implement types for each language and fluency.
        // TODO: Learning Chinese && Japanese
    }

    fn interests() {
        let hobbies = vec![
            "Projects", // 3D game design, embedded programming, AI/ML experimentation.
            "Music",    // Listening to Sleep Token, BMTH and Lorna Shore.
            "Reading",  // Philosophy, tech news, tutorials and blogs.
        ];
    }

}
```
> ### Links
> #### Email: [dhrumilshah.exc@outlook.com](mailto:dhrumilshah.exc@outlook.com)
> #### LinkedIn: [https://www.linkedin.com/in/dhrumil-shah-bssl](https://www.linkedin.com/in/dhrumil-shah-bssl)
> #### Playlist: [Heavy - YT Music](https://music.youtube.com/playlist?list=PLwrG7bLFxMj3E6jjzY_Wtz0NjeFMW8i06)