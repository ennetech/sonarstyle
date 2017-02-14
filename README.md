# sonarstyle
Converts sonarlint-cli html reports in a checkstyle compatible XML, offered as is.

Tested with sonarlint CLI 2.1.0.566

## Usage
You will need php + dom extension to use this tool (```apt update && apt install php7.0 php7.0-xml``` should do the trick)
```
./sonarstyle sonarlint-report.html "prefix_to_files_path" > sonarlint.xml
```

### Questions
- It is pretty? ***no***
- It has 'this advanced' feature? ***no***
- Why you have done that? ***needed sonarlint feedback in my CI/CD pipeline***

## License
MIT
