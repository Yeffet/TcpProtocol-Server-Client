הפרויקט הוא צ'אט ב-C# שמשתמש ב-TCP Sockets(מאפשר תקשורת בין מחשבים ברשת) כדי לאפשר תקשורת בין שרת ללקוח. השרת מאזין לחיבורים ומנהל כמה לקוחות במקביל עם תהליכונים (Threads). הלקוח מתחבר לשרת, שולח הודעות ומקבל תגובות. 
פרוטוקול התקשורת TCP זה פרוטוקול שמבטיח שכל הנתונים יגיעו בשלמותם ובסדר הנכון. 
כדי להפעיל את הפרויקט, קודם מריצים את השרת ואז מפעילים את הלקוח, ואז ניתן לשלוח הודעות ולראות אותן מוצגות גם בצד השרת וגם בצד הלקוח.
