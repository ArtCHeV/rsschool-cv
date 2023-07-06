# [RSSCHOOL-CV](https://artchev.github.io/rsschool-cv/cv)  

## Artem Chernykh

### My Contact Info

**Address:** Saint-Petesburg, Russia  
**Phone:** +79112987237  
**E-mail:** artem.chernykh.v@gmail.com  
**LinkedIn:** [https://www.linkedin.com/in/artchev/](https://www.linkedin.com/in/artchev/)  
**Github:**  [ArtCHeV](https://github.com/ArtCHeV/)

### Summary

I am currently working in technical support, continuously improving my skills and knowledge. I have a passion for good coffee, traveling, and focusing on one thing at a time.

### Skills

- Python (basic knowledge)
- HTML
- CSS
- Git (basic knowledge)
- Windows OS
- Linux (Debian, Armbian)
- Android
- Editors: VS Code
- English A1
- Google advanced search

### Code Example

```python
import string

alf = string.ascii_lowercase

def alphabet_position(text):
    text = text.lower()
    result = ''
    for c in text:
        for i in range(len(alf)):
            if alf[i] == c:
                result += (str(1+i)+' ')
    return result.strip()

