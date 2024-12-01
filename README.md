    class Program
    {
      
        class Character
        {
            public string Name { get; set; }
         

        
            public Character(string name, string quote)
            {
                Name = name;
              
            }

           
            public void Speak()
            {
                Console.WriteLine(Name + "Transformer");
            }
        }

        
    }

