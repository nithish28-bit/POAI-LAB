likes(mary, food).
likes(mary, wine).
likes(john, wine).
likes(john, mary).

likes(john, X) :- likes(mary, X).
likes(john, Y) :- likes(Y, wine).
likes(john, Y) :- likes(Y, Y).

:- initialization(main).

main :-
    likes(john, food),
    write('John likes food'),
    nl,
    likes(john, wine),
    write('John likes wine'),
    nl,
    halt.
% Rule to find the minimum of two numbers
minimum(X, Y, X) :- X =< Y.
minimum(X, Y, Y) :- X > Y.

% Rule to find the maximum of two numbers
maximum(X, Y, X) :- X >= Y.
maximum(X, Y, Y) :- X < Y.

% Main program
:- initialization(main).

main :-
    minimum(50, 20, Min),
    maximum(50, 20, Max),
    write('Minimum = '),
    write(Min),
    nl,
    write('Maximum = '),
    write(Max),
    nl,
    halt.
