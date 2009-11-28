(set fib x (cond (eq x 0) 1 (+ (fib (- x 1)) x)))

(set range (quote begin end) (cond (eq begin end) (quote) (cons begin (range (+ begin 1) end))))
(set len list (cond (eq list (quote)) 0 (+ 1 (len (rest list)))))
(set map (quote fun list) (cond (eq list (quote)) (quote) (cons (fun (first list)) (map fun (rest list)))))

(set testrange (range 1 8))

(print (len testrange))
(print testrange)
(print (map fib testrange))