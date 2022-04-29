## New Tabs Instructions

1. Copy existing Page Content into your code editor 
2. Isolate old tabs and cut/paste into another code editor tab for later reference 
3. Place `<!-- Tabs start --> <!-- Tabs end -->` comment where old tabs were on the page 
4. Delete any tabs-related Jquery code on the page: ex. `$('#[jquery ui tabs id]').tabs();` 
5. Copy/paste page content from code editor back into CMS page 
6. Add Custom Code module to page and name it Tabs 
7. Copy/paste provided demo tab code into custom code module and click Add then Update 
8. Close custom code window and save page changes 
9. Move custom code module from the top of Body Content to between Tabs comment and save 
10. View DEV page to confirm new tab demo is in place 
11. Open the Tabs custom code module and copy/paste code to code editor - Also open old tabs code from Step 2 
12. Add/subtract number of tab titles/sections needed to match old tabs 
13. Copy old tab titles `<li><a href="#tabs-1">COPY TITLE</a></li>` into new tabs `<button class="tab is-active" role="tab" aria-selected="true" aria-controls="tab1-tab" id="tab1">Paste TITLE</button>` 
14. Copy same tab titles into `data-title=“Paste TITLE”` attribute in each tab `<SECTION>` 
15. Make sure `<BUTTON>` and `<SECTION>` attributes match tab numbering 
16. Copy old tab content from between `<div id="tabs-X”> into new tab code between <div class="ootb-tabcordion--entry-content">` for each tab 
17. Find/Replace https://www.coredev.com with blank to remove domain URL from anchor/img tags if necessary 
18. Copy final new tabs code back into custom code module and click update, then save page 
19. Review new tabs on DEV page 
20. Test accessibility functionality by clicking on first tab, then use right/left arrow keys to select tab, then push space bar to switch tabs 
21. View page in mobile - Tabs should switch to vertical accordion style and open and close when tapped
