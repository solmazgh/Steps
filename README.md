# Steps

function steps(n) {
    for (let i = 1; i <= n; i++) {
        let step = "";

        step += "#".repeat(i);
        step += " ".repeat(n - i);

        console.log(step);

    }

}
