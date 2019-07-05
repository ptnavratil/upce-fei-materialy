## Dealokace prostředků
Modifikujte příklad `<atexit.c>` tak, aby se používala jediná funkce registrovaná pomocí atexit(3) - finish(). V této funkci dealokujte alokované prostředky (dealokace nealokovaných bude považována za chybu). Stávající dealokační funkce v programu ponechte, jen je nepoužijte. (Usnadní to kontrolu.) Program pojmenujte `<atexit-once.c>`.
