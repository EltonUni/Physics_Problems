# Sekcja 3: Fale

## 1. Właściwości fal

Fala dźwiękowa w powietrzu ma częstotliwość 440 Hz. Jeśli prędkość dźwięku w powietrzu wynosi 343 m/s, jaka jest jej długość fali? Jaka jest jej długość fali w wodzie, gdzie prędkość dźwięku wynosi 1482 m/s?

## 2. Harmoniki struny

Struna gitarowa ma długość 64 cm i częstotliwość podstawową (jedną strzałkę) równą 330 Hz. Jaka jest prędkość fali na tej strunie?

## 3. Zasada superpozycji

Dwie fale opisane są równaniami $y_1(x, t) = A \sin(kx - \omega t)$ oraz $y_2(x, t) = A \sin(kx + \omega t)$. Jakie jest równanie powstałej fali stojącej? Określ położenia węzłów.

## 4. Echolokacja

Osoba krzyczy w kierunku klifu i słyszy echo 4,0 sekundy później. Jak daleko znajduje się klif? (Prędkość dźwięku w powietrzu wynosi 343 m/s).

## 6. Równanie falowe

Fala opisana jest równaniem $y(x,t) = 0.05 \sin(2\pi x - 50\pi t)$, gdzie x i y są w metrach, a t w sekundach. Wyznacz dla tej fali:

a) Amplitudę

b) Długość fali

c) Częstotliwość

d) Prędkość

## 7. Różnica faz

Jaka jest różnica faz w radianach między dwoma punktami na fali, które są oddalone od siebie o odległość $\lambda/3$?

## 8. Mody fali stojącej

Fala stojąca z czterema strzałkami powstaje na strunie o długości L = 80 cm. Jaka jest długość tej fali?

## 9. Fale

Która z poniższych funkcji może opisywać falę biegnącą? (Wskazówka: sprawdź, czy spełnia równanie falowe $\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$)

a) $y(x,t) = A \cos(kx^2 - \omega t)$

b) $y(x,t) = A(x-vt)^2$

c) $y(x,t) = A \log(x+vt)$

## 10. Rezonans

Wyznacz częstotliwość fali stojącej z dwiema strzałkami na strunie gitarowej, zakładając, że prędkość fali wynosi 1500 m/s, a długość struny to 1,0 m.

## 11. Animacja: Źródła fal

Napisz animację HTML, w której możliwe jest umieszczanie punktów, które będą służyć jako źródła fal opisanych równaniem:

$$
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_0}|^\alpha} \sin(k |\vec{r} - \vec{r_0}| - \omega t)
$$

gdzie $\vec{r_0}$ to pozycja punktu, a $\alpha$ to parametr, który można ustawić w zakresie $[0, 2]$. Animacja powinna pokazywać superpozycję fal ze wszystkich punktów.

## 12. Animacja: Interferencja na dwóch szczelinach

Napisz animację HTML symulującą doświadczenie Younga, w którym dwie szczeliny działają jak punktowe źródła fal koherentnych. Przemieszczenie fali wypadkowej jest sumą fal cząstkowych opisanych wzorem:

$$
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_1}|} \sin(k |\vec{r} - \vec{r_1}| - \omega t) + \frac{A}{|\vec{r}-\vec{r_2}|} \sin(k |\vec{r} - \vec{r_2}| - \omega t)
$$

gdzie $\vec{r_1}$ i $\vec{r_2}$ to wektory położenia szczelin. Użytkownik powinien mieć możliwość zmiany odległości między szczelinami $d = |\vec{r_1} - \vec{r_2}|$ oraz długości fali $\lambda$. Animacja powinna wizualizować wynikowy obraz interferencyjny w czasie rzeczywistym.

## 13. Animacja: Zasada Huygensa

Stwórz interaktywną animację HTML/JavaScript wizualizującą propagację fali w ośrodku dyskretnym. Obszar roboczy powinien być wypełniony siatką punktów („atomów”), które mogą przekazywać drgania swoim sąsiadom.

Zaimplementuj mechanizm, w którym każdy wzbudzony punkt staje się źródłem nowej fali elementarnej (wtórnej). Animacja powinna umożliwiać:

* **Wzbudzenie punktowe:** kliknięcie w pojedynczy atom wyzwala rozchodzącą się falę kulistą.
* **Wzbudzenie liniowe:** jednoczesne aktywowanie rzędu atomów, aby zaobserwować, jak sumowanie wielu fal elementarnych tworzy płaskie czoło fali (obwiednię).
* **Regulację gęstości siatki:** suwak pozwalający użytkownikowi zmieniać zagęszczenie atomów, aby zweryfikować, jak wpływa to na ciągłość i jakość widocznego czoła fali.

Celem jest wizualne zademonstrowanie, jak superpozycja fal cząstkowych tworzy makroskopowe czoło fali.