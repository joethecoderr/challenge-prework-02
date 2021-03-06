# challenge-prework-02
Recap: Curso Básico de Algoritmos

## Retos:

2. Crea un algoritmo para cocinar un huevo.

```
BEGIN
IF eggs == True then:
    OUTPUT "Will be your eggs boiled??"
    INPUT answer
    IF answer == "yes" then:
        fill_pot_with_water()
        light_fire()
        put_eggs_in_pot()
        wait_20_minutes()
        turn_off_fire()
        get_eggs_from_pot()
        lay_eggs_to_rest_5_minutes()
        take_off_shell()
        to_serve())
    END IF
    ELSE IF answer == "no" then:
        BOOLEAN jam, spinachs, cheese, salt, pepper
        INPUT jamon, espinacas, queso, sal, pimienta
        
        light_fire()
        put_cooking_oil_to_pan()
        
        OUTPUT "How would you like your eggs? 1)Fried 2)Omelette 3)Scrambled"
        INPUT eggs_style

        IF eggs_style == "fried" then:
            crack_and_put_them_to_pan()
            spice_up(bool: salt, bool: pepper)
            wait_for_cooking(int: minutes) //according to personal taste
            OUTPUT "Both sides fried?"
            INPUT both_sides_fried
            IF both_sides_fried == "yes" THEN:
                flip_egg()
                wait_for_cooking(int:minutes) //according to personal taste
                to_serve()
            END IF
            ELSE IF both_sides_fried == "no" THEN:
                to_serve()
            END ELSE IF
        ELSE IF eggs_style == "Omelette"  and cheese == True THEN:
            crack_and_beat_eggs()
            spice_up(bool: pepper, bool: salt)
            put_mix_in_pan()
            wait_3_minutes()
            add_ingredients(bool: spinachs, bool: cheese, bool: salt, bool: pepper)
            fold_in_half()
            turn_off_fire
            to_serve()
        END ELSE IF
        ELSE IF eggs_style == "Scrambled" THEN:
            crack_eggs_and_put_in_pan()
            IF jam == True:
                cut_and_add_jam()
            spice_up(bool: pepper, bool: salt)
            WHILE eggs_is_raw:
                shake()
            END WHILE
            to_serve()
    END ELSE IF
    ELSE:
        OUTPUT "Choose a valid option :("
            



```

2. Crea un algoritmo para pedir una pizza

```
BEGIN
OUTPUT "Will you order your pizza through phone call or mobile app?"
INPUT answer
IF answer == "phone call" THEN:
    get_phone_and_dial()
    select_size_and_ingredients()
    FOREACH ingredient in ingredients:
        IF ingredient IS NOT available:
            choose_another_ingredient()
    specify_your_address()
    wait_patiently()
    pay_total_to_delivery_man()
    take_pizza()

ELSE:
    open_app()
    choose_a_pizza_restaurant()
    choose_pizza_size())
    choose_pizza_type()
    add_extras()
    choose_payment_method()
    placer_order()
    wait_patiently()
    IF payment_method == "Cash" THEN:
        pay_total_to_delivery_man()
    take_pizza()
```

3. Crea un algoritmo para que represente la funcionalidad de un cajero automatico.

```
BEGING
OUTPUT "Welcome. Insert your card or press the button for withdrawal of money without card"
tries_counter = 0
IF button_is_pressed THEN:
    OUTPUT "Go to you banking app, choose withdraway without card and type in here the code in your phone screen"
    INPUT code
    
    IF check_code(code) IS TRUE THEN:
        withdrawal()
    END IF
    ELSE:
        OUTPUT "Wrong code. Try again"
        INPUT code
     
        IF check_code(code) IS FALSE THEN:
            OUTPUT "Wrong code. Try again later"
    END ELSE
END IF

ELSE IF card_is_inserted:
    IF counter < 3 THEN:
        read_chip_info()
        OUTPUT "Please type your PIN"
        INPUT pin
        check_pin(pin)
        IF check_pin(pin) IS TRUE THEN:
            display_menu()
        END IF
            
        ELSE:
            OUTPUT "WRONG PIN, TRY AGAIN"
            counter += 1
        END ELSE
     ELSE:
        OUTPUT "Number of tries exceeded. Card Blocked."
     END ELSE
   END IF
END ELSE IF


function display_menu:
    OUTPUT "Choose an option 1)Withdrawal funds 2)Check balance 3)Check movementes 4)Exit"
    INPUT selection
    SWITCH(selection):
        case 1:
            withdrawal()
        case 2:
            OUTPUT "Your balance is: " + balance
        case 3:
            display_recent_movementes()
        case 4:
            close_application()
            
function withdrawal():
    OUTPUT "Type amount to withdrawal"
    INPUT amount
    IF enough_cash_in_atm(amount) IS TRUE AND enough_funds_in_account(amount) THEN:
        count_money()
        give_money()
    END IF
    ELSE IF enough_cash_in_atm IS NOT TRUE THEN:
        OUTPUT "Sorry, I don't have enough cash right now!"
    END ELSE IF
    ELSE IF enough_funds_in_account IS FALSE THEN:
        OUTPUT "Sorry, you dont have enough funds!"
        
    END ELSE IF
    
            
```

## Pasos a seguir:

1. Hacer un "Fork" de este proyecto.
2. Revolver los retos propuestos.
3. Edita este documento "README.md" con la solucion a tus retos.
4. Crear un Pull Request hacia este repositorio.

## ¿Cómo contribuir?

Si quieres agregar o mejorar algo, te invito a colaborar directamente en este repositorio: [challenge-prework-02](https://github.com/platzimaster/challenge-prework-01/)

## Licencia

challenge-prework-02 se lanza bajo la licencia [MIT](https://opensource.org/licenses/MIT).
