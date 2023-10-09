# github-docs-example

# reference to github flavoured markdown for documentation markdown

Reference: 
# Title 1
## Title 2
*italicize* 

**bold**

## Code blocks 
*uses backticks*
```
function getTimeOfDay() {
  const currentTime = new Date();
  const currentHour = currentTime.getHours();

  if (currentHour >= 5 && currentHour < 12) {
    return "Good morning!";
  } else if (currentHour >= 12 && currentHour < 17) {
    return "Good afternoon!";
  } else {
    return "Good evening!";
  }
}

// Example usage:
const greeting = getTimeOfDay();
console.log(greeting);
```

To create lists:
- code block 1
- code block 2

Applying colour syntax to your code blocks
``` python
import datetime

def get_time_of_day():
    current_time = datetime.datetime.now()
    current_hour = current_time.hour

    if 5 <= current_hour < 12:
        return "Good morning!"
    elif 12 <= current_hour < 17:
        return "Good afternoon!"
    else:
        return "Good evening!"

# Example usage:
greeting = get_time_of_day()
print(greeting)

```

Use markdown code blocks for errors too or comments
> This is a code error block
 ```
```

## References
- [Terraform by HashiCorp](https://www.terraform.io/)
- [Infrastructure as Code by RedHat](https://www.redhat.com/en/topics/automation/what-is-infrastructure-as-code-iac#:~:text=choose%20Red%20Hat%3F-,Overview,to%20edit%20and%20distribute%20configurations.)

## Styling text 
- This is a <sub>subscript</sub> text
- This is a <sup>superscript </sup> text

Let's use checkboxes 
- [ ] Checkbox 1
- [ ] Checkbox 2
- [x] Checkbox 3
- [x] Checkbox 4
