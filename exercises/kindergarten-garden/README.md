# Kindergarten Garden

Given a diagram, determine which plants each child in the kindergarten class is
responsible for.

The kindergarten class is learning about growing plants. The teacher
thought it would be a good idea to give them actual seeds, plant them in
actual dirt, and grow actual plants.

They've chosen to grow grass, clover, radishes, and violets.

To this end, the children have put little cups along the window sills, and
planted one type of plant in each cup, choosing randomly from the available
types of seeds.

```text
[window][window][window]
........................ # each dot represents a cup
........................
```

There are 12 children in the class:

- Alice, Bob, Charlie, David,
- Eve, Fred, Ginny, Harriet,
- Ileana, Joseph, Kincaid, and Larry.

Each child gets 4 cups, two on each row. Their teacher assigns cups to
the children alphabetically by their names.

The following diagram represents Alice's plants:

```text
[window][window][window]
VR......................
RG......................
```

In the first row, nearest the windows, she has a violet and a radish.  In the
second row she has a radish and some grass.

Your program will be given the plants from left-to-right starting with
the row nearest the windows. From this, it should be able to determine
which plants belong to each student.

For example, if it's told that the garden looks like so:

```text
[window][window][window]
VRCGVVRVCGGCCGVRGCVCGCGV
VRCCCGCRRGVCGCRVVCVGCGCV
```

Then if asked for Alice's plants, it should provide:

- Violets, radishes, violets, radishes

While asking for Bob's plants would yield:

- Clover, grass, clover, clover

## Setup

Go through the setup instructions for Javascript to install the necessary
dependencies:

[https://exercism.io/tracks/javascript/installation](https://exercism.io/tracks/javascript/installation)

## Requirements

Please `cd` into exercise directory before running all below commands.

Install assignment dependencies:

```bash
$ npm install
```

## Making the test suite pass

Execute the tests with:

```bash
$ npm test
```

In the test suites all tests but the first have been skipped.

Once you get a test passing, you can enable the next one by changing `xtest` to
`test`.


## Submitting Solutions

Once you have a solution ready, you can submit it using:

```bash
exercism submit kindergarten-garden.js
```

## Submitting Incomplete Solutions

It's possible to submit an incomplete solution so you can see how others have
completed the exercise.

## Exercise Source Credits

Random musings during airplane trip. [http://jumpstartlab.com](http://jumpstartlab.com)

