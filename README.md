# Mulesoft

INPUT: {
  "langs": [
    {
      "name": "Bar",
      "language": "Scala"
    },
    {
      "name": "Foo",
      "language": "Java"
    },
    {
      "name": "FooBar",
      "language": "Java"
    }
  ]
}

OUTPUT: 
{
  "langs": [
    {
      "Scala": [
        {
          "name": "Bar"
        }
      ]
    },
    {
      "Java": [
        {
          "name": "Foo"
        },
        {
          "name": "FooBar"
        }
      ]
    }
  ]
}
