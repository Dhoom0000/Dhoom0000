![banner](./assets/banner-top.jpg)
# `Hello, World!`
```rust
//! Welcome To My GitHub Page.
```

```rust
// #[derive(He, Him)]
struct Me;

const NAME: &str = "Dhrumil Shah";

// Contact Me! Looking for jobs!
const LOCATION: &str    = "Cambridge, UK";
const EMAIL: &str       = "dhrumilshah.exc@outlook.com";
const LINKEDIN: &str    = "https://www.linkedin.com/in/dhrumil-shah-bssl";
```

```rust
/// # About Me
impl About for Me {
    // I love coding and problem-solving.
    fn summary() -> String {
        format!(
            "\n\
            Computer Science student focused on Embedded Systems, \
            Machine Learning, Game Development, and Cybersecurity. \
            Skilled in Rust, C/C++, Python, and Java, with \
            experience building practical, maintainable \
            software and applying Agile, debugging, and \
            UI/UX methodologies.
            "
        )
    }
    // procastination and self-confidence is the key *(O v O)*
    fn what_im_upto() -> String {
        format!(
            "\n\
            - Working on a Bevy game for my Final Project. \n
            - Trying out Burn-rs (a sanskrit llm is gonna be funny) \n
            - Capturing the flags on PicoCTF. \n
            "
        )
    }
}
```

```rust
/// # Education
impl Education for Me {

    fn bachelors() -> String {
        // Bachelor's Degree - Currently enrolled
        let bachelors_degree = "B.Eng. (Hons) Computer Science";
        let b_institution = "Anglia Ruskin University, Cambridge";
        let b_year_of_attendance = "2023 - 2026";

        format!("\n{bachelors_degree} \n{b_institution} \n{b_year_of_attendance}")
    }

    fn masters() -> String {
        // Master's Degree - Future Plans
        let masters_degree = "M.Sc. Cyber Security";
        let m_institution = "Anglia Ruskin University, Cambridge";
        let m_year_of_attendance = "2026-2027";

        format!("\n{masters_degree} \n{m_institution} \n{m_year_of_attendance}")
    }
}
```

```rust
/// # Skills
impl Skills for Me {
    fn skills() -> (Vec<String>, Vec<String>, Vec<String>, Vec<String>) 
    {
        // C language, C++, C#, Java, Python, Rust, MATLAB, SQL, Typescript
        let programming = vec!["C", "C++", "C#", "Java", "Python", "Rust", "MATLAB", "SQL", "Typescript"];

        // Git, GitHub, Linux (Kali, and Arch), AWS, Docker, Figma, Bevy ECS
        let tools = vec!["Git", "GitHub", "Linux", "AWS", "Docker", "Figma", "Bevy ECS"];

        // I love being mindful of how UI and UX looks like and how accessible it is for users.
        let methodologies = vec!["Debugging", "UI/UX", "Accessibility", "Agile", "Prototyping", "Object-Oriented"];

        // Duolingo is good.
        let spoken_languages = vec![
            "English - Fluent",
            "Hindi - Fluent",
            "Gujarati - Fluent",
            "German - Beginner",
            ];
        // FIXME: implement types for each language and fluency.
        // TODO: Learn Chinese && Japanese

        (programming, tools, methodologies, spoken_languages)
    }

    // Helper function (pls ignore)
    fn skills_to_string() -> String {
        let (programming, tools, methodologies, spoken_languages) = Self::skills();

        format!(
            "\nProgramming: {} \nTools: {} \nMethodologies: {} \nLanguages: {}",
            programming.join(", "),
            tools.join(", "),
            methodologies.join(", "),
            spoken_languages.join(", ")
        )
    }
}
```

```rust
/// # My Interests
impl Hobbies for Me {
    fn interests() -> String {
        let hobbies = vec![
            "Projects", // 3D game design, embedded programming, AI/ML experimentation.
            "Music",    // Listening to Sleep Token, BMTH and Lorna Shore.
            "Reading",  // Philosophy, tech news, tutorials and blogs.
            "Writing",  // Quotes, Philosophy, Fiction.
        ];

        format!(
            "\n{}",
            hobbies.join(", ")
        )
    }
}
```

> ### Links
> #### Email: [dhrumilshah.exc@outlook.com](mailto:dhrumilshah.exc@outlook.com)
> #### LinkedIn: [https://www.linkedin.com/in/dhrumil-shah-bssl](https://www.linkedin.com/in/dhrumil-shah-bssl)
> #### Playlist: [Heavy - YT Music](https://music.youtube.com/playlist?list=PLwrG7bLFxMj3E6jjzY_Wtz0NjeFMW8i06)

![banner](./assets/banner-top.jpg)