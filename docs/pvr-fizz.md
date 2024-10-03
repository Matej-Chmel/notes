# Fizz buzz

Klasická úloha pro ověření dělitelnosti.

```rs
fn capitalize_first_letter(s: &mut String) {
    if let Some(first_char) = s.chars().next() {
        let capitalized_char = first_char.to_uppercase().to_string();
        *s = capitalized_char + &s[1..];
    }
}

fn main() {
    for i in 1..=100 {
        let items = [
            i.to_string(),
            String::from("Fizz"),
            String::from("Buzz"),
            String::from("FizzBuzz"),
        ];

        let fizz = (i % 3 == 0) as usize;
        let buzz = (i % 5 == 0) as usize * 2usize;
        let result = &items[fizz + buzz];

        println!("{i:0>3}: {result}");
    }
}

// fn orig_main() {
//     for i in 1..=100 {
//         let mut result = String::new();
//
//         if i % 3 == 0 {
//             result.push_str("fizz");
//         }
//
//         if i % 5 == 0 {
//             result.push_str("buzz")
//         }
//
//         if result.is_empty() {
//             result = i.to_string()
//         } else {
//             capitalize(&mut result);
//         }
//
//         println!("{i:0>3}: {}", result)
//     }
// }
```