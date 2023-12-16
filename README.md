# elite_aps_econometrics
Parser and linear regression for prices of elite apartments in Moscow (econometrics project)

Econometrics research of elite apartments in Moscow. 500 apartments from https://m2.ru/moskva/nedvizhimost/kupit-kvartiru/?districtIds=103&districtIds=81&districtIds=182&districtIds=218&districtIds=15&districtIds=60&districtIds=164&districtIds=37&districtIds={page_num}

EDA: data cleaning, data vizualization and vizual analysis.

Linear regression model: simple linreg model using statsmodels.api (same results with sklearn, but there are more needed statistics for econometrics)

Hypothesis testing: hypothesis about the significance of regression coefficients, hypotheses  about coefficients affect on the prices.

Libraries used: pandas+numpy, matplotlib & seaborn, statsmodels, scipy.stats

Features: area (m^2), rooms (amount of rooms), floor_live, floor_total, zone (categorical), neighborhood (categorical), distance (from the city center, km), time (from the nearest subway, min). Categorical features were encoded usin One-Hot-Encoding

Актуальность: рынок жилой недвижимости испытывает статистически значимый рост, который особенно заметен в мегаполисах, таких как Москва. В последнее время в столице наблюдалось интенсивное строительство и внедрение новых жилых проектов. Эти факторы делают рынок недвижимости привлекательным для потенциальных инвесторов. Факты и выводы, полученные в ходе нашей проектной работы, могут стать ценной информацией для инвесторов. Понимание факторов, влияющих на
ценообразование элитной недвижимости, позволит определять справедливую стоимость объектов для целей принятия инвестиционных решений (Например, поиск недооцененных лотов на рынке с последующей их покупкой для перепродажи за короткий срок – от 1-го до 2-ух лет). Исследование создает основу для выбора наилучшего экономического решения, оптимальной тактики и стратегии на данном рынке.
