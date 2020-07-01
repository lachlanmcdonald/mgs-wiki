> **stairs_stringer** is a **[Stairs Brushes](Stairs-Brushes)** that generates stairs with a stringer of a specific height.

- [Parameters](#parameters)
- [Direction](#direction)

## Parameters

- **Direction**: The facing direction of the stairs
- **Count**: The number of runs to fit within the brushes dimensions. If the box's dimensions are not divisible by the count, the depth of each run will be inconsistent.
- **Height**: The height of each run
- **Stringer**: The height of the stringer (the area extending beneath each run)

## Direction

<table>
    <tr>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_direction0.png" alt="Example of a direction of 0"></td>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_direction1.png" alt="Example of a direction of 1"></td>
    </tr>
    <tr>
        <td>Direction: <code>0</code></td>
        <td>Direction: <code>1</code></td>
    </tr>
    <tr>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_direction2.png" alt="Example of a direction of 2"></td>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_direction3.png" alt="Example of a direction of 3"></td>
    </tr>
    <tr>
        <td>Direction: <code>2</code></td>
        <td>Direction: <code>3</code></td>
    </tr>
</table>

## Stringer

<table>
    <tr>
        <td width="33%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_stringer1.png" alt="Example of a Stringer of 1"></td>
        <td width="33%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_stringer2.png" alt="Example of a Stringer of 2"></td>
        <td width="33%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.3/stairs_stringer_stringer4.png" alt="Example of a Stringer of 3"></td>
    </tr>
    <tr>
        <td>Stringer: <code>1</code></td>
        <td>Stringer: <code>2</code></td>
        <td>Stringer: <code>4</code></td>
    </tr>
</table>