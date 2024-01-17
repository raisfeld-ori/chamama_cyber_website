<script>
    import projects from '$lib/images/projects.jpg';
    import chamama from '$lib/images/chamama.png'
    import Card from './Card.svelte';
    
    let text = [
        `בית ספר החממה זה בית ספר ללמידה אישית
        לכן במגמה שלנו אנחנו נעזרים בקורסים אונליין ומנטורים כדי ללמוד
        על מנת להתקדם בלמידה שאנחנו התלמדים רוצים להתקדם בה
        כול תלמדים במגמה בוחר לבד מה הם רוצים ללמוד
        !אם זה בניית אתרים, סייבר, הכנת משחקים ועוד
        כול חודש/חודשיים אנחנו מציגים פרוייקט שמראה מה למדנו בתקופה
        בעזרת החומר שאנחנו לומדים כול תקופה אנחנו מציגים את היכולות שלנו`,
        `
        Consequat aliquip excepteur dolor cupidatat eu tempor amet sint laborum culpa.
        Et velit exercitation aliqua sunt pariatur aliqua ipsum enim reprehenderit et sunt cillum sint sit.
        Eu quis voluptate ad duis non fugiat quis exercitation. Duis nostrud culpa elit dolor enim anim cillum ex qui minim non.
        Officia Lorem ex consequat nulla ut veniam nulla Lorem occaecat laboris nulla. Et ullamco ea dolore exercitation reprehenderit sint esse qui reprehenderit ex et.
        `,
        `
        Sunt laborum culpa ipsum mollit do in tempor officia minim officia anim excepteur ut nulla.
        Anim aliquip adipisicing labor veniam ipsum ad nulla ullamco cupidatat qui.
        Eiusmod sunt qui irure enim est consectetur deserunt duis sit mollit eiusmod laboris est id.
        Consectetur cillum dolor duis enim labore proident excepteur
        `
    ];
 </script>
 
 <Card image={[projects, chamama, chamama]} {text} header={[`?איך אנחנו לומדים`, `הלמידה בשנה ראשונה`, 'הלמידה בשנה שנייה']} />