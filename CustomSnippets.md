# Custom Snippets in VS Code
Ctrl + Shift + P to open search function

Search "snippet" and select "Configure User Snippets"

Select programming language

Modify json to add custom snippets

## Example for C#:
```json
"Modifyed xUnit Test": {
		"prefix": "fact",
		"body": [
		  "[Fact]",
		  "public void TestName()",
		  "{",
		  "\t// Arrange",
		  "\t",
		  "\t// Act",
		  "\t",
		  "\t// Assert",
		  "",
		  "}"
		],
		"description": "Modifyed xUnit Test"
	  }
```
## Result
```C#
[Fact]
public void TestName()
{
    // Arrange
    
    // Act
    
    // Assert

}
```