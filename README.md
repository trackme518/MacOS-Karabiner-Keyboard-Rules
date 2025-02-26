# MacOS Karabiner Keyboard Rules
 Rules for Karabiner on MacOS to behave as PC Czech Keyboard


## Semicolon
```
{
    "description": "semicolon",
    "manipulators": [
        {
            "from": {
                "key_code": "non_us_backslash",
                "modifiers": {
                    "mandatory": [],
                    "optional": ["any"]
                }
            },
            "to": [
                {
                    "key_code": "semicolon",
                    "modifiers": ["right_option"]
                }
            ],
            "type": "basic"
        },
        {
            "from": {
                "key_code": "semicolon",
                "modifiers": {
                    "mandatory": ["right_option"],
                    "optional": ["any"]
                }
            },
            "to": [
                {
                    "key_code": "non_us_backslash",
                    "modifiers": []
                }
            ],
            "type": "basic"
        }
    ]
}
```

## Curly brackets
```
{
    "description": "{} brackets",
    "manipulators": [
        {
            "from": {
                "key_code": "b",
                "modifiers": {
                    "mandatory": ["right_option"],
                    "optional": ["any"]
                }
            },
            "to": [
                {
                    "key_code": "9",
                    "modifiers": ["right_option"]
                }
            ],
            "type": "basic"
        },
        {
            "from": {
                "key_code": "n",
                "modifiers": {
                    "mandatory": ["right_option"],
                    "optional": ["any"]
                }
            },
            "to": [
                {
                    "key_code": "0",
                    "modifiers": ["right_option"]
                }
            ],
            "type": "basic"
        }
    ]
}
```

## Square brackets
```
{
    "description": "[] brackets",
    "manipulators": [
        {
            "from": {
                "key_code": "f",
                "modifiers": {
                    "mandatory": ["right_option"],
                    "optional": ["any"]
                }
            },
            "to": [
                {
                    "key_code": "open_bracket",
                    "modifiers": ["right_option"]
                }
            ],
            "type": "basic"
        },
        {
            "from": {
                "key_code": "g",
                "modifiers": {
                    "mandatory": ["right_option"],
                    "optional": ["any"]
                }
            },
            "to": [
                {
                    "key_code": "close_bracket",
                    "modifiers": ["right_option"]
                }
            ],
            "type": "basic"
        }
    ]
}
```