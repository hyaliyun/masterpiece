const QUOTES = [
  {
    thumbnail: require('./quotes/pos.png'),
    name: 'Alexandre Dumas',
    title: translate({
      id: 'homepage.quotes.christopher-chedeau.title',
      message: 'The Count of Monte Cristo',
      description: 'The Count of Monte Cristo',
    }),
    text: (
      <Translate
        id="homepage.quotes.christopher-chedeau"
        description="Quote of Christopher Chedeau on the home page">
         "All human wisdom is contained in these four words: 'wait' and 'hope'!"
      </Translate>
    ),
  },
  {
    thumbnail: require('./quotes/shop.png'),
    name: 'Lu Yao',
    title: translate({
      id: 'homepage.quotes.hector-ramos.title',
      message: 'Ordinary World',
      description: 'Ordinary World',
    }),
    text: (
      <Translate
        id="homepage.quotes.hector-ramos"
        description="Quote of Hector Ramos on the home page">
        "Life is so unpredictable. There is no eternal pain, nor eternal happiness. Life is like flowing water, sometimes so smooth, sometimes so tortuous."
      </Translate>
    ),
  },
  {
    thumbnail: require('./quotes/wordpress.png'),
    name: 'Tolstoy',
    title: translate({
      id: 'homepage.quotes.risky-vetter.title',
      message: 'Anna Karenina',
      description: 'Tolstoy',
    }),
    text: (
      <Translate
        id="homepage.quotes.risky-vetter"
        description="Quote of Ricky Vetter on the home page">
        Happy families are all happy in the same way, but every unhappy family is unhappy in its own way.
      </Translate>
    ),
  },
];
