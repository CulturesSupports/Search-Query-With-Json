# Search-Query-With-Json
Query App For Searching Json Web Links / Kind of Mini Search Engine inside Bootstrap




------------------


# How its Made 


Entire app is inside `index.html` file 



- includes Json inside < javascript > < / javascript> 

- included id for Search Query
- Include Css for Styling Components 

------

Search is Working for Typing ``` Words into Search Bar ```

https://culturessupports.github.io/Search/



----------------------

Json is data fitting into  < javascript > < / javascript> and both enable write json funtion to preview inside html app id tags 


-------------



For making a App info work inside search  You Need to Feed the Json Links and Json Parameters


--------------

# Develop inside copilot chat 


```

JSON Data: The JSON object searchQueries contains search queries along with their results. 40 Home Cooking urls


```

https://github.com/copilot



Paste the  ` index.html ` source code  inside the copilot chat and continue paste the prompts to correcting search urls

-------

```

JSON Data: The JSON object searchQueries contains search queries along with their results. 10 Weather urls


```


```

JSON Data: The JSON object searchQueries contains search queries along with their results. 5 cake reciept urls


```

```

JSON Data: The JSON object searchQueries contains search queries along with their results. 10 Car Repair urls


```

```

JSON Data: The JSON object searchQueries contains search queries along with their results. 10 mobile app urls


```

- This is to Getting Json Data inside  `index.html`


---------------

---------------

---------------

---------------

---------------

---------------

---------------

---------------

---------------


```

 <script>
    const searchQueries = [
      
    {
      "query": "apple nutrition facts",
      "timestamp": "2025-02-14T07:00:00Z",
      "results": [
        {
          "title": "Apple Nutrition Facts",
          "snippet": "An apple is a sweet, edible fruit produced by an apple tree.",
          "url": "https://www.healthline.com/nutrition/apple-nutrition"
        },
        {
          "title": "Calories in Apple",
          "snippet": "Find detailed information on apple nutrition, including calories, vitamins, and more.",
          "url": "https://www.calorieking.com/foods/calories-in-apple/YtMWpDWYQjBzFhD-Av2nFA"
        }
      ]
    },
    {
      "query": "how to tie a tie",
      "timestamp": "2025-02-14T07:05:00Z",
      "results": [
        {
          "title": "How to Tie a Tie",
          "snippet": "Learn how to tie a tie with this step-by-step guide.",
          "url": "https://www.ties.com/how-to-tie-a-tie"
        },
        {
          "title": "How to Tie a Tie: Easy Step-by-Step Instructions",
          "snippet": "Follow these easy instructions to tie a perfect knot every time.",
          "url": "https://www.realmenrealstyle.com/how-to-tie-a-tie/"
        }
      ]
    },
    {
      "query": "best travel destinations 2025",
      "timestamp": "2025-02-14T07:10:00Z",
      "results": [
        {
          "title": "Top Travel Destinations for 2025",
          "snippet": "Discover the best travel destinations for 2025.",
          "url": "https://www.lonelyplanet.com/best-in-travel"
        },
        {
          "title": "Where to Travel in 2025",
          "snippet": "Find the best places to visit in 2025.",
          "url": "https://www.travelandleisure.com/best-places-to-travel-2025"
        }
      ]
    },
    {
      "query": "current weather in Tokyo",
      "timestamp": "2025-02-14T07:15:00Z",
      "results": [
        {
          "title": "Tokyo Weather Forecast",
          "snippet": "Get the latest weather updates for Tokyo.",
          "url": "https://www.weather.com/weather/today/l/Tokyo+Japan"
        },
        {
          "title": "Tokyo Weather",
          "snippet": "Check the current weather conditions in Tokyo.",
          "url": "https://www.accuweather.com/en/jp/tokyo/226396/weather-forecast/226396"
        }
      ]
    },
    {
      "query": "how to bake a cake",
      "timestamp": "2025-02-14T07:20:00Z",
      "results": [
        {
          "title": "How to Bake a Cake",
          "snippet": "Learn how to bake a cake with this simple recipe.",
          "url": "https://www.allrecipes.com/recipe/17481/simple-white-cake/"
        },
        {
          "title": "Cake Baking Tips",
          "snippet": "Get tips and tricks for baking the perfect cake.",
          "url": "https://www.bbcgoodfood.com/howto/guide/baking-cake-tips"
        }
      ]
    },
    {
      "query": "top programming languages 2025",
      "timestamp": "2025-02-14T07:25:00Z",
      "results": [
        {
          "title": "Top Programming Languages for 2025",
          "snippet": "Explore the most popular programming languages in 2025.",
          "url": "https://www.techrepublic.com/article/top-programming-languages/"
        },
        {
          "title": "Best Programming Languages to Learn",
          "snippet": "Find out which programming languages are worth learning in 2025.",
          "url": "https://www.codingdojo.com/blog/7-most-in-demand-programming-languages/"
        }
      ]
    },
    {
      "query": "benefits of meditation",
      "timestamp": "2025-02-14T07:30:00Z",
      "results": [
        {
          "title": "The Benefits of Meditation",
          "snippet": "Discover the physical and mental benefits of meditation.",
          "url": "https://www.mindful.org/meditations-for-beginners/"
        },
        {
          "title": "How Meditation Improves Health",
          "snippet": "Learn how meditation can improve your overall health.",
          "url": "https://www.healthline.com/nutrition/12-benefits-of-meditation"
        }
      ]
    },
    {
      "query": "history of the internet",
      "timestamp": "2025-02-14T07:35:00Z",
      "results": [
        {
          "title": "History of the Internet",
          "snippet": "Explore the history and development of the internet.",
          "url": "https://www.history.com/topics/inventions/invention-of-the-internet"
        },
        {
          "title": "How the Internet Was Born",
          "snippet": "Learn about the origins of the internet.",
          "url": "https://www.cnn.com/interactive/2025/03/specials/cnntech/internet-history/"
        }
      ]
    },
    {
      "query": "latest smartphone reviews",
      "timestamp": "2025-02-14T07:40:00Z",
      "results": [
        {
          "title": "Latest Smartphone Reviews",
          "snippet": "Read the latest reviews of the newest smartphones.",
          "url": "https://www.cnet.com/topics/phones/"
        },
        {
          "title": "Best Smartphones of 2025",
          "snippet": "Find the best smartphones available in 2025.",
          "url": "https://www.techradar.com/best/best-phone"
        }
      ]
    },
    {
      "query": "beginner yoga poses",
      "timestamp": "2025-02-14T07:45:00Z",
      "results": [
        {
          "title": "Beginner Yoga Poses",
          "snippet": "Learn the basic yoga poses for beginners.",
          "url": "https://www.yogajournal.com/poses/types/beginner"
        },
        {
          "title": "10 Yoga Poses for Beginners",
          "snippet": "Start your yoga journey with these beginner poses.",
          "url": "https://www.self.com/gallery/yoga-for-beginners-poses"
        }
      ]
    },
    {
      "query": "benefits of drinking water",
      "timestamp": "2025-02-14T07:50:00Z",
      "results": [
        {
          "title": "Health Benefits of Drinking Water",
          "snippet": "Discover the many health benefits of staying hydrated.",
          "url": "https://www.medicalnewstoday.com/articles/290814"
        },
        {
          "title": "Why Drinking Water is Important",
          "snippet": "Learn why drinking enough water is crucial for your health.",
          "url": "https://www.healthline.com/nutrition/7-health-benefits-of-water"
        }
      ]
    },
    {
      "query": "how to lose weight fast",
      "timestamp": "2025-02-14T07:55:00Z",
      "results": [
        {
          "title": "How to Lose Weight Fast",
          "snippet": "Find effective methods to lose weight quickly.",
          "url": "https://www.healthline.com/nutrition/how-to-lose-weight-as-fast-as-possible"
        },
        {
          "title": "Rapid Weight Loss Tips",
          "snippet": "Explore tips and tricks for rapid weight loss.",
          "url": "https://www.webmd.com/diet/obesity/ss/slideshow-best-diet-tips-ever"
        }
      ]
    },
    {
      "query": "best books of 2025",
      "timestamp": "2025-02-14T08:00:00Z",
      "results": [
        {
          "title": "Best Books of 2025",
          "snippet": "Check out the top books to read in 2025.",
          "url": "https://www.goodreads.com/choiceawards/best-books-2025"
        },
        {
          "title": "Top Books to Read in 2025",
          "snippet": "Discover the best books to read this year.",
          "url": "https://time.com/collection/must-read-books/"
        }
      ]
    },
     {
      "query": "latest smartphone reviews",
      "timestamp": "2025-02-14T07:40:00Z",
      "results": [
        {
          "title": "Latest Smartphone Reviews",
          "snippet": "Read the latest reviews of the newest smartphones.",
          "url": "https://www.cnet.com/topics/phones/"
        },
        {
          "title": "Best Smartphones of 2025",
          "snippet": "Find the best smartphones available in 2025.",
          "url": "https://www.techradar.com/best/best-phone"
        }
      ]
    },
    {
      "query": "top programming languages 2025",
      "timestamp": "2025-02-14T07:25:00Z",
      "results": [
        {
          "title": "Top Programming Languages for 2025",
          "snippet": "Explore the most popular programming languages in 2025.",
          "url": "https://www.techrepublic.com/article/top-programming-languages/"
        },
        {
          "title": "Best Programming Languages to Learn",
          "snippet": "Find out which programming languages are worth learning in 2025.",
          "url": "https://www.codingdojo.com/blog/7-most-in-demand-programming-languages/"
        }
      ]
    },
    {
      "query": "AI advancements 2025",
      "timestamp": "2025-02-14T08:10:00Z",
      "results": [
        {
          "title": "AI Advancements in 2025",
          "snippet": "Discover the latest advancements in artificial intelligence in 2025.",
          "url": "https://www.forbes.com/sites/forbestechcouncil/2025/01/01/the-latest-advancements-in-ai/"
        },
        {
          "title": "Top AI Trends for 2025",
          "snippet": "Learn about the top AI trends and technologies for 2025.",
          "url": "https://www.zdnet.com/article/top-ai-trends-for-2025/"
        }
      ]
    },
    {
      "query": "blockchain technology 2025",
      "timestamp": "2025-02-14T08:15:00Z",
      "results": [
        {
          "title": "Blockchain Technology in 2025",
          "snippet": "Explore how blockchain technology is evolving in 2025.",
          "url": "https://www.coindesk.com/learn/blockchain-technology-evolution-2025/"
        },
        {
          "title": "The Future of Blockchain",
          "snippet": "Find out what the future holds for blockchain technology.",
          "url": "https://www.ibm.com/blockchain/2025-future"
        }
      ]
    },
    {
      "query": "virtual reality trends 2025",
      "timestamp": "2025-02-14T08:20:00Z",
      "results": [
        {
          "title": "Virtual Reality Trends for 2025",
          "snippet": "Discover the latest trends in virtual reality for 2025.",
          "url": "https://www.vrworld.com/latest-trends-in-vr-2025/"
        },
        {
          "title": "Top VR Technologies in 2025",
          "snippet": "Learn about the top virtual reality technologies in 2025.",
          "url": "https://www.techradar.com/news/top-vr-technologies-2025"
        }
      ]
    },
    {
      "query": "cloud computing innovations 2025",
      "timestamp": "2025-02-14T08:25:00Z",
      "results": [
        {
          "title": "Cloud Computing Innovations in 2025",
          "snippet": "Explore the latest innovations in cloud computing for 2025.",
          "url": "https://www.cloudcomputing-news.net/articles/cloud-computing-innovations-2025/"
        },
        {
          "title": "Future of Cloud Computing",
          "snippet": "Learn about the future of cloud computing technologies.",
          "url": "https://www.ibm.com/cloud-computing/future-2025"
        }
      ]
    },
    {
      "query": "quantum computing 2025",
      "timestamp": "2025-02-14T08:30:00Z",
      "results": [
        {
          "title": "Quantum Computing in 2025",
          "snippet": "Discover the advancements in quantum computing for 2025.",
          "url": "https://www.scientificamerican.com/quantum-computing-2025/"
        },
        {
          "title": "The Future of Quantum Computing",
          "snippet": "Learn about the future prospects of quantum computing.",
          "url": "https://www.techrepublic.com/article/future-of-quantum-computing/"
        }
      ]
    },
    {
      "query": "robotics technology 2025",
      "timestamp": "2025-02-14T08:35:00Z",
      "results": [
        {
          "title": "Robotics Technology in 2025",
          "snippet": "Explore the latest advancements in robotics technology for 2025.",
          "url": "https://www.robotics.org/blogs/robotics-technology-2025/"
        },
        {
          "title": "Future of Robotics",
          "snippet": "Learn about the future trends in robotics.",
          "url": "https://www.technologyreview.com/future-of-robotics-2025/"
        }
      ]
    },
    {
      "query": "5G technology 2025",
      "timestamp": "2025-02-14T08:40:00Z",
      "results": [
        {
          "title": "5G Technology in 2025",
          "snippet": "Discover how 5G technology is transforming the world in 2025.",
          "url": "https://www.cnet.com/5g-technology-2025/"
        },
        {
          "title": "The Impact of 5G",
          "snippet": "Learn about the impact of 5G technology on various industries.",
          "url": "https://www.techradar.com/impact-of-5g-2025"
        }
      ]
    },
    {
      "query": "cybersecurity trends 2025",
      "timestamp": "2025-02-14T08:45:00Z",
      "results": [
        {
          "title": "Cybersecurity Trends for 2025",
          "snippet": "Explore the latest trends in cybersecurity for 2025.",
          "url": "https://www.csoonline.com/cybersecurity-trends-2025/"
        },
        {
          "title": "Top Cybersecurity Threats",
          "snippet": "Learn about the top cybersecurity threats in 2025.",
          "url": "https://www.kaspersky.com/top-cybersecurity-threats-2025"
        }
      ]
    },
    {
      "query": "Internet of Things (IoT) 2025",
      "timestamp": "2025-02-14T08:50:00Z",
      "results": [
        {
          "title": "Internet of Things in 2025",
          "snippet": "Discover the latest developments in IoT for 2025.",
          "url": "https://www.iotworldtoday.com/IoT-2025/"
        },
        {
          "title": "Future of IoT",
          "snippet": "Learn about the future trends in Internet of Things.",
          "url": "https://www.ibm.com/iot/future-trends-2025"
        }
      ]
    },
    {
      "query": "biotechnology advancements 2025",
      "timestamp": "2025-02-14T08:55:00Z",
      "results": [
        {
          "title": "Biotechnology Advancements in 2025",
          "snippet": "Explore the latest advancements in biotechnology for 2025.",
          "url": "https://www.biotechnews.com/advancements-2025/"
        },
        {
          "title": "Future of Biotechnology",
          "snippet": "Learn about the future prospects of biotechnology.",
          "url": "https://www.nature.com/articles/biotechnology-future-2025"
        }
      ]
    },
    {
      "query": "machine learning applications 2025",
      "timestamp": "2025-02-14T09:00:00Z",
      "results": [
        {
          "title": "Machine Learning Applications in 2025",
          "snippet": "Discover the latest applications of machine learning in 2025.",
          "url": "https://www.mlnews.com/applications-2025/"
        },
        {
          "title": "Future of Machine Learning",
          "snippet": "Learn about the future trends in machine learning.",
          "url": "https://www.forbes.com/sites/future-of-machine-learning/"
        }
      ]
    },


    {
      "query": "how to make diner-style home fries",
      "timestamp": "2025-02-14T07:00:00Z",
      "results": [
        {
          "title": "How To Make Diner-Style Home Fries",
          "snippet": "So good, you could open up your own diner.",
          "url": "https://www.thekitchn.com/how-to-make-diner-style-home-fries-230152"
        }
      ]
    },
    {
      "query": "quick and easy home fries",
      "timestamp": "2025-02-14T07:05:00Z",
      "results": [
        {
          "title": "Quick and Easy Home Fries",
          "snippet": "These home fries turn out crispy every time. They're great for breakfast or as a side dish.",
          "url": "https://www.allrecipes.com/recipe/71803/quick-and-easy-home-fries/"
        }
      ]
    },
    {
      "query": "home fries recipe",
      "timestamp": "2025-02-14T07:10:00Z",
      "results": [
        {
          "title": "Home Fries",
          "snippet": "Home Fries are the ultimate in comfort-food side dishes. They brown beautifully and have a rich flavor that both your grownup and kid friends will love.",
          "url": "https://www.myrecipes.com/recipe/home-fries"
        }
      ]
    },
    {
      "query": "best home cooking blogs",
      "timestamp": "2025-02-14T07:15:00Z",
      "results": [
        {
          "title": "Home Cooking Adventure - A Food Blog with Tested Recipes Using Everyday Ingredients",
          "snippet": "Home Cooking Adventure - A Food Blog with Tested Recipes Using Everyday Ingredients",
          "url": "https://www.homecookingadventure.com/"
        }
      ]
    },
    {
      "query": "classic comfort food dinners",
      "timestamp": "2025-02-14T07:20:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "easy dinner ideas",
      "timestamp": "2025-02-14T07:25:00Z",
      "results": [
        {
          "title": "67 Easy Dinner Ideas We Love - Taste of Home",
          "snippet": "67 Easy Dinner Ideas We Love Home Recipes Meal Types Dinner",
          "url": "https://www.tasteofhome.com/collection/easy-dinner-ideas/"
        }
      ]
    },
    {
      "query": "best home-cooked meals",
      "timestamp": "2025-02-14T07:30:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "best comfort food recipes",
      "timestamp": "2025-02-14T07:35:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "easy home cooking recipes",
      "timestamp": "2025-02-14T07:40:00Z",
      "results": [
        {
          "title": "67 Easy Dinner Ideas We Love - Taste of Home",
          "snippet": "67 Easy Dinner Ideas We Love Home Recipes Meal Types Dinner",
          "url": "https://www.tasteofhome.com/collection/easy-dinner-ideas/"
        }
      ]
    },
    {
      "query": "best home cooking blogs",
      "timestamp": "2025-02-14T07:45:00Z",
      "results": [
        {
          "title": "Home Cooking Adventure - A Food Blog with Tested Recipes Using Everyday Ingredients",
          "snippet": "Home Cooking Adventure - A Food Blog with Tested Recipes Using Everyday Ingredients",
          "url": "https://www.homecookingadventure.com/"
        }
      ]
    },
    {
      "query": "best home-cooked meals",
      "timestamp": "2025-02-14T07:50:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "easy home cooking recipes",
      "timestamp": "2025-02-14T07:55:00Z",
      "results": [
        {
          "title": "67 Easy Dinner Ideas We Love - Taste of Home",
          "snippet": "67 Easy Dinner Ideas We Love Home Recipes Meal Types Dinner",
          "url": "https://www.tasteofhome.com/collection/easy-dinner-ideas/"
        }
      ]
    },
    {
      "query": "best comfort food recipes",
      "timestamp": "2025-02-14T08:00:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "best home-cooked meals",
      "timestamp": "2025-02-14T08:05:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "easy home cooking recipes",
      "timestamp": "2025-02-14T08:10:00Z",
      "results": [
        {
          "title": "67 Easy Dinner Ideas We Love - Taste of Home",
          "snippet": "67 Easy Dinner Ideas We Love Home Recipes Meal Types Dinner",
          "url": "https://www.tasteofhome.com/collection/easy-dinner-ideas/"
        }
      ]
    },
    {
      "query": "best comfort food recipes",
      "timestamp": "2025-02-14T08:15:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    },
    {
      "query": "best home-cooked meals",
      "timestamp": "2025-02-14T08:20:00Z",
      "results": [
        {
          "title": "94 Classic Dinner Foods & Home-Cooked Meals - Taste of Home",
          "snippet": "94 Classic Dinner Foods & Home-Cooked Meals Home Recipes Cooking Style Comfort Food",
          "url": "https://www.tasteofhome.com/collection/classic-comfort-food-dinners/"
        }
      ]
    }

      
      
    ];

    document.getElementById('searchInput').addEventListener('input', function() {
      const query = this.value.toLowerCase();
      const results = searchQueries.filter(item => item.query.toLowerCase().includes(query));
      displayResults(results);
    });

    function displayResults(results) {
      const resultsList = document.getElementById('resultsList');
      resultsList.innerHTML = '';
      results.forEach(item => {
        const listItem = document.createElement('li');
        listItem.className = 'list-group-item bg-dark text-light';

        const queryTitle = document.createElement('h5');
        queryTitle.textContent = item.query;
        listItem.appendChild(queryTitle);

        item.results.forEach(result => {
          const resultTitle = document.createElement('p');
          resultTitle.innerHTML = `<strong>${result.title}:</strong> ${result.snippet} <a href="${result.url}" target="_blank" class="text-light">[Link]</a>`;
          listItem.appendChild(resultTitle);
        });

        resultsList.appendChild(listItem);
      });
    }
  </script>

```

### The Copilot can be use to generate the json data needed inside ` index.html ` inside this repository





```


    {
      "query": "apple nutrition facts",
      "timestamp": "2025-02-14T07:00:00Z",
      "results": [
        {
          "title": "Apple Nutrition Facts",
          "snippet": "An apple is a sweet, edible fruit produced by an apple tree.",
          "url": "https://www.healthline.com/nutrition/apple-nutrition"
        },
        {
          "title": "Calories in Apple",
          "snippet": "Find detailed information on apple nutrition, including calories, vitamins, and more.",
          "url": "https://www.calorieking.com/foods/calories-in-apple/YtMWpDWYQjBzFhD-Av2nFA"
        }
      ]
    },



```


### this is the query urls in json you need to develop more of by 10 urls by category 


### This enables the search query app to generate more and more search , the more links you generate and put inside


### it can be used to serve over 10 000 search  
---------------

---------------

---------------
# This Project is Meaned for Making a Mini Search Engine With 10 000 Url Links
---------------

---------------

---------------

---------------

