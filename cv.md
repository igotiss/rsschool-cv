1. **Full name:**  Igor Tyshchenko
2. **Contacts:**
    + Adress: Ukraine, Vinnytsa    
    + Phone: +380673066188 
    + email: igotiss@gmail.com
    
3. **Short summary:**
    + *My Goal:*        
        - І want to get additional programming skills, gain new experience
        - The desire to receive moral satisfaction from work, to be proud of achievements 
    + *My Priorities:*
        - Work in a team
        - Preliminary planning for efficient problem solving
    + *My strengths:*
        - Fast-learner
        - Self-motivated
        - Determined
        - Success-oriented
        - Team player
        - Hardworking
        - Intelligence
        - able to prioritize
        - able to work independently with little or no supervision
        - open to change
   
4. **Skills:**
    + HTML
    + CSS
    + JS
    + Wordpress, Joomla
    + JQUERY
    + Preprocessors 
    + PHP
    + Laravel
    + GIT
    + SOLID

5. **Example of code:**
    +  ```Php laravel
          class AccountController extends Controller
          {
             /** Show all accounts
             *
             * @return \Illuminate\Contracts\View\Factory|\Illuminate\View\View
             */
             public function index()
            {
              $accounts = Account::where('is_active', 1)->get();
              $currencies = Currency::all();
              $total = Account::getTotal($accounts);
              $totalGrn = 0;

              foreach ($total as $key => $item){
                $totalGrn += $item * Currency::find($key)->rate;
               }

              return view('pages.accounts', compact('accounts', 'total', 'currencies', 'totalGrn'));
              }   
       ```
   
 6. **Еxperience:**
    + [Malyatko](https://www.https://www.malyatko.vn.ua/) - [Code Malytko in bitbucket.org](https://bitbucket.org/mishakatsan/malyatko/src/master/)
    + [cpo.vn.ua](http://cpo.vn.ua/) without code, just WP
    + [mrt.lutsk.ua](http://mrt.lutsk.ua/) without code, just WP
    + [vmc.vn.ua](http://vmc.vn.ua/) without code, just Joomla 
 
 7. **Education:**
    + National Pirogov Memorial Medical University, Vinnytsya, 2002, medical department
    + PhD Normal Phisyology, 2017
    + Self-education
    + [Coursera Building Web Applications in PHP](https://www.coursera.org/learn/web-applications-php)
    + [QATestLab](https://training.qatestlab.com/)
    + [HTML academy](https://htmlacademy.ru/)  
  8. **English:** intermediate
