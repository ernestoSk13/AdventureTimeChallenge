# AdventureTimeChallenge

Open xcode and create and app where you have to make choices to get to a final path. You have to consume a JSON file and represent it either on a CollectionView, Table View or a Navigation. View system. The user has to be available to get to a final statement and return to the main statement if they get lost.

```
{
  "statement": {
    "id": "Q61435",
    "displayText": "This is a dimly lit forest, with large trees all around.",
    "choices": [
      {
        "id": "A69244",
        "sequenceNumber": 0,
        "displayText": "Go South",
        "statement": {
          "id": "Q65963",
          "displayText": "Storm-tossed trees block your way."
        }
      },
      {
        "id": "A69245",
        "sequenceNumber": 1,
        "displayText": "Go East",
        "statement": {
          "id": "Q65964",
          "displayText": "You are in a clearing, with a forest surrounding you on all sides. A path leads south.",
          "choices": [
            {
              "id": "A69246",
              "sequenceNumber": 0,
              "displayText": "Go North",
              "statement": {
                "id": "Q65965",
                "displayText": "The forest becomes impenetrable to the north."
              }
            },
            {
              "id": "A69247",
              "sequenceNumber": 1,
              "displayText": "Go South",
              "statement": {
                "id": "Q65966",
                "displayText": "You are standing in an open field west of a white house, with a boarded front door.",
                "choices": [
                  {
                    "id": "A69248",
                    "sequenceNumber": 1,
                    "displayText": "Go East",
                    "statement": {
                      "id": "Q65967",
                      "displayText": "The door is boarded and you can't remove the boards."
                    }
                  },
                  {
                    "id": "A69249",
                    "sequenceNumber": 0,
                    "displayText": "Go North",
                    "statement": {
                      "id": "Q65968",
                      "displayText": "You are facing the north side of a white house. In one corner of the house there is a small window which is slightly ajar. To the north a narrow path winds through the trees.",
                      "choices": [
                        {
                          "id": "A69250",
                          "sequenceNumber": 0,
                          "displayText": "Go North",
                          "statement": {
                            "id": "Q65969",
                            "displayText": "You come to edge of a gaping chasm.  You slip on the loose gravel and fall to your death."
                          }
                        },
                        {
                          "id": "A69241",
                          "sequenceNumber": 1,
                          "displayText": "Look in window",
                          "statement": {
                            "id": "Q65970",
                            "displayText": "You can see what appears to be a kitchen.  Unfortunately, it is the last thing you see because you just died."
                          }
                        }
                      ]
                    }
                  }
                ]
              }
            }
          ]
        }
      }
    ]
  }
}

```
