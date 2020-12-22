# eccom-store-imm-project
imm_final webstore project
sam waters

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Plato's Cave Bookstore]</title>
    <meta name="onlinestore for a bookstore" content="[ a bookstore focused on used and new books that bring back classic literature and philosophy]">
    <meta name="author" content="[Sam Waters]">
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <link rel="stylesheet" href="css/style.css">
  </head>
  <body>
    <header class="page-header">
      <a href="index.html" class="logo"><img src="img/pLATOSCAVE.png" alt="pLATOSCAVE"><!-- Site logo --></a>

      <!-- Navigation menu and toggle button (non-functional) -->
      <button type="button" class="nav-toggle">
        <span class="material-icons">menu</span>
      </button>
      <nav aria-label="Primary" class="navigation">
        <ul class="menu">
          <li><a href="#">Shop</a>
            <ul class="submenu">
              <li><a href="#">Philosophy</a></li>
              <li><a href="#">Classic Literature</a></li>
              <li><a href="#">Modern Literature</a></li>
            </ul>
          </li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>

      <!-- Search for a product (non-functional) -->
      <form class="search">
        <label>Search
          <input type="search" name="find" id="find">
        </label>
        <button type="button"><span class="material-icons">search</span></button>
      </form>

      <!-- Additional links -->
      <ul class="your-products">
        <li><a href="#"><span class="material-icons" aria-label="Favourites">favorite_border</span></a></li>
        <li><a href="#"><span class="material-icons" aria-label="Items in your cart">shopping_cart</span></a></li>
      </ul>
    </header>

    <main class="products">
      <header class="heading">
        <h1>Sale On Classic Literature</h1>
      </header>

      <!-- Filtering product form -->
      <form class="filters">
        <h2>Search</h2>

        <div class="filter-options">
          <fieldset>
            <legend>Language</legend>
            <ul class="filter-list">
              <li><input type="checkbox" name="language" value="black" id="black"> <label for="black">English</label></li>
              <li><input type="checkbox" name="language" value="white" id="white"> <label for="white">French</label></li>
              <li><input type="checkbox" name="lanuage" value="grey" id="grey"> <label for="grey">Spanish</label></li>
              <li><input type="checkbox" name="language" value="red" id="red"> <label for="red">Chinese</label></li>
              <li><input type="checkbox" name="language" value="blue" id="blue"> <label for="blue">Other</label></li>
            </ul>
          </fieldset>
          <fieldset>
            <legend>Print Verison</legend>
            <ol class="filter-list">
              <li><input type="checkbox" name="verison" value="p" id="p"> <label for="p">Paperback</label></li>
              <li><input type="checkbox" name="version" value="h" id="h"> <label for="h">Hardcover</label></li>
            </label></li>
            </ol>
          </fieldset>
          <fieldset>
            <legend>Ratings (above)</legend>
            <ol class="filter-list">
              <li>
                <input type="radio" name="rating" value="4" id="aboveFour">
                <label for="aboveFour">
                  <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_border</span>
                </label>
              </li>
              <li>
                <input type="radio" name="rating" value="3" id="aboveThree">
                <label for="aboveThree">
                  <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_border</span><span class="material-icons">star_border</span>
                </label>
              </li>
              <li>
                <input type="radio" name="rating" value="2" id="aboveTwo">
                <label for="aboveTwo">
                  <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_border</span><span class="material-icons">star_border</span><span class="material-icons">star_border</span>
                </label>
              </li>
              <li>
                <input type="radio" name="rating" value="1" id="aboveOne">
                <label for="aboveOne">
                  <span class="material-icons">star</span><span class="material-icons">star_border</span><span class="material-icons">star_border</span><span class="material-icons">star_border</span><span class="material-icons">star_border</span>
                </label>
              </li>
            </ol>
          </fieldset>
        </div>
        <fieldset>
          <label for="sort">Show</label>
          <select name="sort" id="sort">
            <option value="price-high">Price, highest to lowest</option>
            <option value="price-low">Price, lowest to highest</option>
            <option value="newest">Newest releases</option>
          </select>
        </fieldset>
      </form>

      <section class="results">
        <h2 class="subheading">Results</h2>

        <!-- Product 1 -->
        <article class="product">
          <header>
            <img src="img/product1.png" alt="PLAtO'S republic ">
            <h3>Plato's Republic</h3>
            <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
            <p>Plato''s The Republic is widely acknowledged as the cornerstone of Western philosophy.

              Presented in the form of a dialogue between Socrates and three different interlocutors, it is an inquiry into the notion of a perfect community and the ideal individual within it. During the conversation other questions are raised: what is goodness; what is reality; what is knowledge? The Republic also addresses the purpose of education and the role of both women and men as "guardians" of the people. With remarkable lucidity and deft use of allegory, Plato arrives at a depiction of a state bound by harmony and ruled by "philosopher kings."
              
              For more than seventy years, Penguin has been the leading publisher of classic literature in the English-speaking world. With more than 1,700 titles, Penguin Classics represents a global bookshelf of the best works throughout history and across genres and disciplines. Readers trust the series to provide authoritative texts enhanced by introductions and notes by distinguished scholars and contemporary authors, as well as up-to-date translations by award-winning translators.
            </p>
            <dl>
              <dt>Rating</dt>
              <dd>4.9 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r"> English</label></li>
                <li><label><input type="radio" name="colour" value="w"> French</label></li>
                <li><label><input type="radio" name="colour" value="b"> Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Verison</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m"> Paperback</label></li>
                <li><label><input type="radio" name="size" value="l"> Hardcover</label></li>
            
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>

        <!-- Product 2 -->
        <article class="product">
          <header>
            <img src="img/product2.png" alt="Product Image">
            <h3>THUS SPOKE ZARATHUSTRA: A BOOK FOR EVERYONE AND NO ONE
    
           </h3>
            <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
            <p>Friedrich Nietzsche''s most accessible and influential philosophical work, misquoted, misrepresented, brilliantly original and enormously influential

              Nietzsche was one of the most revolutionary and subversive thinkers in Western philosophy, and Thus Spoke Zarathustra remains his most famous and influential work. It describes how the ancient Persian prophet Zarathustra descends from his solitude in the mountains to tell the world that God is dead and that the Superman, the human embodiment of divinity, is his successor. Nietzsche''s utterance ''God is dead'', his insistence that the meaning of life is to be found in purely human terms, and his doctrine of the Superman and the will to power were all later seized upon and unrecognisably twisted by, among others, Nazi intellectuals. With blazing intensity and poetic brilliance, Nietzsche argues that the meaning of existence is not to be found in religious pieties or meek submission to authority, but in an all-powerful life force: passionate, chaotic and free. 
              
              For more than seventy years, Penguin has been the leading publisher of classic literature in the English-speaking world. With more than 1,700 titles, Penguin Classics represents a global bookshelf of the best works throughout history and across genres and disciplines. Readers trust the series to provide authoritative texts enhanced by introductions and notes by distinguished scholars and contemporary authors, as well as up-to-date translations by award-winning translators.
            </p>
            <dl>
              <dt>Rating</dt>
              <dd>4.4 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r">English</label></li>
                <li><label><input type="radio" name="colour" value="w"> French</label></li>
                <li><label><input type="radio" name="colour" value="b"> Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Verison</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m">Paperback</label></li>
                <li><label><input type="radio" name="size" value="l">Hardcover</label></li>
                
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>

        <!-- Product 3 -->
        <article class="product">
          <header>
            <img src="img/product3.png" alt="Product Image">
            <h3>THE ART OF WAR & OTHER CLASSICS OF EASTERN PHILOSOPHY</h3>
            <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
            <p>The words of the ancient Chinese sages are as timeless as they are wise.

              The words of ancient Chinese philosophers have influenced other thinkers across the world for more than 2,000 years, and continue to shape our ideas today. The Art of War & Other Classics of Eastern Philosophy includes translations of Sun Tzu's Art of War, Lao-Tzu's Tao Te Ching, the teachings of the master sage Confucius, and the writings of Mencius. From insights on warfare and diplomacy to advice on how to deal with one's neighbors and colleagues, this collection of classical Eastern philosophy will provide readers with countless nuggets of wisdom.
              
              IBPA Benjamin Franklin Gold Award Winner 2017!
              </p>
            <dl>
              <dt>Rating</dt>
              <dd>4.2 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r">English</label></li>
                <li><label><input type="radio" name="colour" value="w">French</label></li>
                <li><label><input type="radio" name="colour" value="b">Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Verison</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m">Paperback</label></li>
                <li><label><input type="radio" name="size" value="l">Hardcopy</label></li>
                
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>
  
        <!-- Product 4 -->
        <article class="product">
          <header>
            <img src="img/product4.png" alt="Product Image">
            <h3> The Prince</h3>
            <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
            <p> HarperCollins is proud to present its incredible range of best-loved, essential classics.'We have declared before that it is not only expedient but necessary for a prince to take care his foundations be good, otherwise his fabric will be sure to fail.'Considered one of the first works of modern philosophy, Machiavelli's The Prince is an intense study on the nature of power and the course it should take when ruling a country and expresses the author's strong and unyielding ideals and beliefs on using force rather than law to achieve your aims.Responsible for the widely-used phrase 'Machiavellian', with all of its negative connotations, his extreme treatise remains a classic text to this day.</p>
            <dl>
              <dt>Rating</dt>
              <dd>4.4 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r">English</label></li>
                <li><label><input type="radio" name="colour" value="w">French</label></li>
                <li><label><input type="radio" name="colour" value="b">Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Veriosn</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m">Paperback</label></li>
                <li><label><input type="radio" name="size" value="l">Hardcover</label></li>
  
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>

        <!-- Product 5 -->
        <article class="product">
          <header>
            <img src="img/product5.png" alt="Product Image">
            <h3>CRITIQUE OF PURE REASON</h3>
            <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
            <p>
              The masterpiece of the father of modern philosophy 
              
              A seminal text of modern philosophy, Immanuel Kant''s Critique of Pure Reason (1781) made history by bringing together two opposing schools of thought: rationalism, which grounds all our knowledge in reason, and empiricism, which traces all our knowledge to experience. Published here in a lucid reworking of Max Müller''s classic translation, the Critique is a profound investigation into the nature of human reason, establishing its truth, falsities, illusions, and reality.
              
              For more than seventy years, Penguin has been the leading publisher of classic literature in the English-speaking world. With more than 1,700 titles, Penguin Classics represents a global bookshelf of the best works throughout history and across genres and disciplines. Readers trust the series to provide authoritative texts enhanced by introductions and notes by distinguished scholars and contemporary authors, as well as up-to-date translations by award-winning translators
              </p>
            <dl>
              <dt>Rating</dt>
              <dd>4.0 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r"> English</label></li>
                <li><label><input type="radio" name="colour" value="w"> French</label></li>
                <li><label><input type="radio" name="colour" value="b"> Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Verison</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m">Paperback</label></li>
                <li><label><input type="radio" name="size" value="l">Hardcover</label></li>
   
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>

        <!-- Product 6 -->
        <article class="product">
          <header>
            <img src="img/product6.png" alt="Product Image">
            <h3>Meditations</h3>
            <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
            <p>A leading translation of Stoic philosophy in wise and practical aphorisms that have inspired Bill Clinton, Ryan Holiday, Anna Kendrick and many more.

              Written in Greek by an intellectual Roman emperor without any intention of publication, the Meditations of Marcus Aurelius  offer a wide range of fascinating spiritual reflections and exercises developed as the leader struggled to understand himself and make sense of the universe. Spanning from doubt and despair to conviction and exaltation, they cover such diverse topics as the question of virtue, human rationality, the nature of the gods and the values of leadership. But while the Meditations were composed to provide personal consolation, in developing his beliefs Marcus also created one of the greatest of all works of philosophy: a series of wise and practical aphorisms that have been consulted and admired by statesmen, thinkers and ordinary readers for almost two thousand years.
              
              To provide a full understanding of Aurelius''s seminal work, this edition includes explanatory notes, a general index, an index of quotations, an index of names, and an introduction by Diskin Clay putting the work in its biographical, historical, and literary context, a chronology of Marcus Aurelius''s life and career.
              
              For more than seventy years, Penguin has been the leading publisher of classic literature in the English-speaking world. With more than 1,700 titles, Penguin Classics represents a global bookshelf of the best works throughout history and across genres and disciplines. Readers trust the series to provide authoritative texts enhanced by introductions and notes by distinguished scholars and contemporary authors, as well as up-to-date translations by award-winning translators.
              </p>
            <dl>
              <dt>Rating</dt>
              <dd>4.4 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r"> English</label></li>
                <li><label><input type="radio" name="colour" value="w">French</label></li>
                <li><label><input type="radio" name="colour" value="b">Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Verison</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m">Paperback</label></li>
                <li><label><input type="radio" name="size" value="l">Hardcover</label></li>
                
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>


        <!-- Product 7 -->
        <article class="product">
          <header>
            <img src="img/product7.png" alt="Product Image">
            <h3>LETTERS FROM A STOIC</h3>
            <data value="39"><del>$45.00</del> <ins>$30.00</ins></data>
            <p>"It is philosophy that has the duty of protecting us...without it no one can lead a life free of fear or worry."

              For several years of his turbulent life, Seneca was the guiding hand of the Roman Empire. His inspired reasoning derived mainly from the Stoic principles, which had originally been developed some centuries earlier in Athens. This selection of Seneca''s letters shows him upholding the austere ethical ideals of Stoicism—the wisdom of the self-possessed person immune to overmastering emotions and life’s setbacks—while valuing friendship and the courage of ordinary men, and criticizing the harsh treatment  of slaves and the cruelties in the gladiatorial arena. The humanity and wit revealed in Seneca’s interpretation of Stoicism is a moving and inspiring declaration of the dignity of the individual mind.
              
              For more than seventy years, Penguin has been the leading publisher of classic literature in the English-speaking world. With more than 1,700 titles, Penguin Classics represents a global bookshelf of the best works throughout history and across genres and disciplines. Readers trust the series to provide authoritative texts enhanced by introductions and notes by distinguished scholars and contemporary authors, as well as up-to-date translations by award-winning translators.
              
            
              </p>
            <dl>
              <dt>Rating</dt>
              <dd>4.0 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
            </dl>
            <a href="#">see more</a>
          </header>
          <form>
            <fieldset>
              <legend>Language</legend>
              <ul>
                <li><label><input type="radio" name="colour" value="r">English</label></li>
                <li><label><input type="radio" name="colour" value="w"> French</label></li>
                <li><label><input type="radio" name="colour" value="b"> Other</label></li>
              </ul>
            </fieldset>
            <fieldset>
              <legend>Verison</legend>
              <ol>
                <li><label><input type="radio" name="size" value="m">Paperback</label></li>
                <li><label><input type="radio" name="size" value="l">Hardcover</label></li>
                
              </ol>
            </fieldset>
          </form>
          <footer>
            <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
            <button type="button"><span class="material-icons">favorite</span></button>
          </footer>
        </article>

   <!-- Product 8 -->
   <article class="product">
    <header>
      <img src="img/product8.jpg" alt="Product Image">
      <h3>
        THE NICOMACHEAN ETHICS
        </h3>
      <data value="39"><del>$40.00</del> <ins>$34.00</ins></data>
      <p>
        "One swallow does not make a summer; neither does one day. Similarly neither can one day, or a brief space of time, make a man blessed and happy" 
        
        Previously published as Ethics, Aristotle''s The Nicomachean Ethics addresses the question of how to live well and originates the concept of cultivating a virtuous character as the basis of his ethical system. Here Aristotle sets out to examine the nature of happiness, and argues that happiness consists in ''activity of the soul in accordance with virtue'', including moral virtues, such as courage, generosity and justice, and intellectual virtues, such as knowledge, wisdom and insight. The Ethics also discusses the nature of practical reasoning, the value and the objects of pleasure, the different forms of friendship, and the relationship between individual virtue, society and the State. Aristotle''s work has had a profound and lasting influence on all subsequent Western thought about ethical matters. 
        
        This Penguin Classics edition is translated from the Greek by J.A.K. Thomson with revisions and notes by Hugh Tredennick, and an introduction and bibliography by Jonathan Barnes. 
        
        For more than seventy years, Penguin has been the leading publisher of classic literature in the English-speaking world. With more than 1,700 titles, Penguin Classics represents a global bookshelf of the best works throughout history and across genres and disciplines. Readers trust the series to provide authoritative texts enhanced by introductions and notes by distinguished scholars and contemporary authors, as well as up-to-date translations by award-winning translators.
        
        </p>
      <dl>
        <dt>Rating</dt>
        <dd>4.6 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
      </dl>
      <a href="#">see more</a>
    </header>
    <form>
      <fieldset>
        <legend>Colours</legend>
        <ul>
          <li><label><input type="radio" name="colour" value="r"> Red</label></li>
          <li><label><input type="radio" name="colour" value="w"> White</label></li>
          <li><label><input type="radio" name="colour" value="b"> Blue</label></li>
        </ul>
      </fieldset>
      <fieldset>
        <legend>Sizes</legend>
        <ol>
          <li><label><input type="radio" name="size" value="m"> M</label></li>
          <li><label><input type="radio" name="size" value="l"> L</label></li>
          <li><label><input type="radio" name="size" value="xl"> XL</label></li>
        </ol>
      </fieldset>
    </form>
    <footer>
      <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
      <button type="button"><span class="material-icons">favorite</span></button>
    </footer>
  </article>
   <!-- Product 9 -->
   <article class="product">
    <header>
      <img src="img/product9.png" alt="Product Image">
      <h3>ANCIENT GREEK PHILOSOPHERS</h3>
      <data value="39"><del>$70.00</del> <ins>$59.00</ins></data>
      <p>
        "Philosophy begins in wonder."
                                             --Plato
        
        Have you ever wondered about the development of civilization? What topics were discussed in the days of Ancient Greece? This collection of thoughts from Plato, Aristotle, and other masters of philosophy will lead your mind on a journey of enlightened exploration into ethics, morality, law, medicine, and more. With an introduction by a distinguished scholar of classic literature, this beautiful Canterbury Classics bonded-leather volume with gilded edges and specially designed endpapers is sure to be a favorite keepsake edition in your library.
        
        </p>
      <dl>
        <dt>Rating</dt>
        <dd>4.4 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
      </dl>
      <a href="#">see more</a>
    </header>
    <form>
      <fieldset>
        <legend>Language</legend>
        <ul>
          <li><label><input type="radio" name="colour" value="r">English</label></li>
          <li><label><input type="radio" name="colour" value="w"> French</label></li>
          <li><label><input type="radio" name="colour" value="b">Other</label></li>
        </ul>
      </fieldset>
      <fieldset>
        <legend>Verison</legend>
        <ol>
          <li><label><input type="radio" name="size" value="m">Paperback</label></li>
          <li><label><input type="radio" name="size" value="l">Hardcover</label></li>
        
        </ol>
      </fieldset>
    </form>
    <footer>
      <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
      <button type="button"><span class="material-icons">favorite</span></button>
    </footer>
  </article>

   <!-- Product 10-->
   <article class="product">
    <header>
      <img src="img/prodct10.png" alt="Product Image">
      <h3>Divine Comedy</h3>
      <data value="39"><del>$50.00</del> <ins>$39.00</ins></data>
      <p>“O human race, born to fly upward, wherefore at a little wind dost thou so fall?”

        Inferno, Purgatorio, and Paradiso—the three fates of the deceased become the three pillars of an epic poem. The Divine Comedy, written by Italian poet Dante Alighieri in the fourteenth century, is considered the foremost work in Italian literature. The journey begins with Dante’s descent into the depths of Hell where he witnesses those eternally separated from God. Then he climbs the mountain of Purgatory where Christian souls undergo final purification, before finally touring the celestial circles of Heaven where he is filled with the image of God. An allegorical work, the comedy is representative of the soul’s journey towards God. Influential for seven centuries, this classic is a must have for lovers of great literature, and the luxurious leather-bound edition from Canterbury Classics will make a stunning addition to any library.
        
        </p>
      <dl>
        <dt>Rating</dt>
        <dd>4.8 <span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star</span><span class="material-icons">star_half</span></dd>
      </dl>
      <a href="#">see more</a>
    </header>
    <form>
      <fieldset>
        <legend>Lanugage</legend>
        <ul>
          <li><label><input type="radio" name="language" value="e">English</label></li>
          <li><label><input type="radio" name="language" value="f">French</label></li>
          <li><label><input type="radio" name="language" value="o"> Other</label></li>
        </ul>
      </fieldset>
      <fieldset>
        <legend>Verison</legend>
        <ol>
          <li><label><input type="radio" name="verison" value="p"> Paperback</label></li>
          <li><label><input type="radio" name="verison" value="h">hardcover </label></li>
          
        </ol>
      </fieldset>
    </form>
    <footer>
      <button type="button"><span class="material-icons">add_shopping_cart</span> Add to Cart</button>
      <button type="button"><span class="material-icons">favorite</span></button>
    </footer>
  </article>
      </section>

      <nav aria-label="Pagination" class="pagination">
        <p>1-6 of 23 products found</p>
        <ol class="pages">
          <li><a href="#" aria-label="Current Page, Page 1" aria-current="true">1</a></li>
          <li><a href="#" aria-label="Page 2">2</a></li>
          <li><a href="#" aria-label="Page 3">3</a></li>
          <li><a href="#" aria-label="Page 4">4</a></li>
          <li><a href="#" aria-label="Page 5">5</a></li>
        </ol>
      </nav>
    </main>

    <footer class="page-footer">
      <ul class="social">
        <li><a href="#"><span class="material-icons">face</span> Facebook</a></li>
        <li><a href="#"><span class="material-icons">camera_alt</span> Instagram</a></li>
        <li><a href="#"><span class="material-icons">alternate_email</span> Twitter</a></li>
      </ul>
      <nav aria-label="Legal">
        <ul class="legal">
          <li><a href="#">Terms of Use</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">Accessibility Policy</a></li>
        </ul>
      </nav>
      <p class="copyright">&copy; Copyright, 2020.</p>
    </footer>

  </body>
</html>

