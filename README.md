# challenge2_automat_portfolio_martyna_brodka

#   Task 1: Konfiguracja oprogramowania
  ## Subtask 1: Dlaczego zdecydowałam się wziąć udział w wyzwaniu Dare IT Challenge?
    
  Witam, mam na imię Martyna. Niedawno zakończyłam swoje pierwsze wyzwanie z Dare IT - Zostań testerem manualnym. Jako, że dużo wyniosłam z tego kursu, naturalną koleją rzeczy było dla mnie kontynuowanie nauki, tym razem w testowaniu automatycznym z Pythonem. Moim celem jest rozpoczęcie swojej pierwszej pracy w testowaniu oprogramowania. Mam nadzieję, że realizacja tego wyzwania przybliży mnie do niego.

## Subtask 3
 
#   Task 2: Selektory
  ## Subtask 2: Wypisz wszystkie elementy znajdujące się na stronie https://scouts-test.futbolkolektyw.pl/pl/login oraz wymień do nich po 3 selektory

**Przypomnij_hasło_hyperlink_xpath**

//*[@id="__next"]/form/div/div[1]/a

//*[text()="Przypomnij hasło"]

//child::div/a

**Scouts_Panel_heading_xpath**

//*[@id="__next"]/form/div/div[1]/h5

//*[text()="Scouts Panel"]

//*[contains(@class, "MuiTypography-root MuiTypography-h5")]

**Login_input_xpath**

//*[@id="login"]

//*[text()="Login"]

//*[contains(@class, "MuiInputBase-root MuiInput")]

**Hasło_input_xpath**

//*[@id="password"]

//*[text()="Hasło"]

//*[@name="password"]

**Polski_button_xpath**

//*[@id="__next"]/form/div/div[2]/div/div

//*[contains(@class, "MuiSelect-root MuiSelect-select")]

//*[text()="Polski"]

**Zaloguj_button_xpath**

//*[@id="__next"]/form/div/div[2]/button/span[1]

//*[contains(@class, "MuiButton-label")]

//*[text()="Zaloguj"]

  ## Subtask 3: