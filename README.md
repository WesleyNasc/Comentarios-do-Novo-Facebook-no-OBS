ATUALIZAÇÃO 2020/11/11: (ps Wesley Nascimento) Agora você pode usar o código na Nova Versão do Facebook, tanto para os vídeos ao vivo de Pessoas e Páginas, quanto diretamente do Painel da sua própria Live. 
Obs .: 

- O código apensa apresenta as funcionalidades para Lives do Facebook.
- O código não está carregando fotos no momento.

#  Essa atualização é um garfo do código mestre do StudioKrause, ao qual deixo todos os créditos.

---

UPDATE 2020+06-30: Now you can load comments from facebook live. Replace "dock.html" file and code injected into facebook page (from file "paste into 'CSS and Javascript Injection' on Facebook page.txt").

---

Demo: https://www.youtube.com/watch?v=Qc0cyKdevxo

Chrome:
1. Install this extension in Chrome:
https://chrome.google.com/webstore/detail/css-and-javascript-inject/ckddknfdmcemedlmmebildepcmneakaa

2. If you use "new" facebook layout, switch to older version

3. Open Facebook page in Chrome. Click on installed extension (yellow syringe icon) and in tab "Javascript" paste this code:
https://pastebin.com/nhUFTL4R

It will:
- add button "copy" to every comment
- add listener, which will copy the content of the comment when clicking blue "copy" button (beware: it will overwrite your clipboard content!)

You can check it by clicking on blue "copy" button and pasting the content of your clipboard into notepad.

4. Open files "dock.html" and "browser_source.html" in Chrome.


OBS:
1. Go to "View"->"Docks"->"Custom browser docks"
2. Type "FB comments" in "Dock name" column
3. Copy (from Chrome adress bar) location of file "dock.html" and paste into "URL", apply and close - now you got your control panel, you can dock it in OBS.
4. Add new "Browser" source, copy (from Chrome adress bar) location of file "browser_source.html" and past the adress into "URL" field.


To copy / show comment in OBS:
- click on blue "copy" button on Facebook page
- paste the comment into field in OBS
- click "Load" - preview should load below
- click one of two "Show with template" buttons
- you can also add some icons to comment

When you click on textarea, previous content will be erased.
