let a ="i am mahaK shriVastava";
        let b = a.toLowerCase();
        let c = b.split(" ");
        let d = (c.map(check => check.replace(check.at(0), check.at(0).toUpperCase())));
        console.log(d.join(" "));
