# Puppy Robot SDK
Welcome to official developer guide of **Puppy Robot**. This tool lets you control a virtual dog using code.
## Quickstart Guide 
Follow these steps to connect your first  script to the puppy robot.
### 1. Installation
Run the following command in your terminal application:
`pip install puppy-robot-sdk`
### 2. Initialize the code
Paste this Python script into a file named `app.py`:
```python
import puppy_sdk
# Connect to the box
robot = puppy_sdk.connect(token="12345")
# Execute an action
robot.bark()
```
## Common Errors
| Error Code | Meaning | Solution |
| :--- | :--- | :--- |
| `401` | Unauthorized | Check your authentication token |
| `404` | Dog Not Found | Ensure your virtual pet is turned on |

Need more help? Check out [our community forum](https://example.com).