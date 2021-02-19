# Архитектура системы команд

js  -> 0хххххххx хxAAAAAAA - A - Адрес
mov -> 1xxxxx№№№ DDDDDDDDD - № - номер регистра; D - const

# Шина управления

[0] - CLK
[1-2] - № у-ва  (00 - ROM; 10 - REG)
[3] - WR/RD (0 = reg -> bus)