# b2sum

> BLAKE2 மறையீட்டு சரிகாண்தொகையைக் கணி.
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/b2sum>.

- கோப்பின் BLAKE2 சரிகாண்தொகையைக் கணி:

`b2sum {{கோப்பு}}`

- பலக் கோப்புகளின் BLAKE2 சரிகாண்தொகையைக் கணி:

`b2sum {{கோப்பு1}} {{கோப்பு2}}`

- BLAKE2 சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

`b2sum -c {{கோப்பு.b2}}`

- இயல் உள்ளீட்டின் BLAKE2 சரிகாண்தொகையைக் கணி:

`{{கட்டளை}} | b2sum`