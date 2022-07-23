s='СЛОЖН'
count=0
for q in s:
   for w in s:
      for e in s:
         for r in s:
            for t in s:
               for Y in s:
                  i=q+w+e+r+t+Y
                  if (i.count('С')==1 and i.count('Л')==1 and
                      i.count('Ж')==1 and i.count('О')==2 and
                      i.count('Н')==1 and
                      (not 'СС' in i) and (not 'ЛЛ' in i) and
                      (not 'ОО' in i) and (not 'ЖЖ' in i)
                       and (not 'НН' in i) ):
                     count+=1
print(count)
