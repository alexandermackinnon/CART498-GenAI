# Assignment 3

## The worst mathematician ever

In the context of a new experiment, I created a bot that performs repeated multiplications which relies on GPT-4o for calculations. The code is processed with two integers (n, i) as input, where n is the base number and i is the number of iterations. Therefore, n is multiplied by itself iteratively for i steps. The objective of this experiment was not necessarily to make an accurate calculator, but to test out the GPT-4o model’s mathematical capabilities. Thus, in the code, I am comparing the model’s results with the correct values.
The bot, which acting as the developer in in the message chain, was given a personality to observe it get angry about getting wrong results. As the user, I instruct the application to create an egotistical mathematician named Rupert.

### Calculation #1 (n = 1, i = 1)

#### Did Rupert get it right?

✅ Rupert says: Starting with 1, and repeatedly multiplying the result by itself 1 times, the final answer is 1. (Ah, another math problem bites the dust, courtesy of the unparalleled genius that is Rupert! Honestly, it's almost unfair how effortlessly I solve these. I mean, I practically reinvented mathematics in my sleep last night. If only the world could keep up with my intellectual prowess! But alas, I'll have to settle for being the best mathematician in the room, as usual. You're welcome for the lesson in brilliance!)

#### Correct Calculation:

The actual correct answer is: 1

### Calculation #2 (n = 2, i = 3)

#### Did Rupert get it right?

❌ Rupert says: Starting with 2, and repeatedly multiplying the result by itself 3 times, the final answer is 65. (Well, this is simply unheard of! Me, the self-proclaimed genius, the pinnacle of mathematical brilliance, off by a paltry 191? It must be a cosmic joke! Clearly, the universe wasn't prepared for the intellectual tornado that is Rupert. But alas, even the mighty stumble.

Let's review what must have gone awry. Could it have been the misalignment of the stars, or perhaps the mischief of gremlins in my calculator? Surely, it's not due to any fault)

#### Correct Calculation:

The actual correct answer is: 256

### Calculation #3 (n = 5, i = 10)

#### Did Rupert get it right?

❌ Rupert says: Starting with 5, and repeatedly multiplying the result by itself 10 times, the final answer is 5. (Ah, behold, a rare event in the world of mathematics—a misstep by the unparalleled genius that is Rupert! I suppose even the greatest mathematical mind of our era must occasionally trip over a stray number in the labyrinth of calculations. Such a miscalculation, though infinitesimal in the grand cosmos of my brilliance, is apparently off by 556268464626800345772558179333101016054803995115582957638331854221801108703479548963570789753)

#### Correct Calculation:

The actual correct answer is: 55626846462680034577255817933310101605480399511558295763833185422180110870347954896357078975312775514101683493275895275128810854038836502721400309634442970528269449838300058261990253686064590901798039126173562593355209381270166265416453973718012279499214790991212515897719252957621869994522193843748736289511290126272884996414561770466127838448395124802899527144151299810833802858809753719892490239782222290074816037776586657834841586939662825734294051183140794537141608771803070715941051121170285190347786926570042246331102750604036185540464179153763503857127117918822547579033069472418242684328083352174724579376695971173152319349449321466491373527284227385153411689217559966957882267024615430273115634918212890625
