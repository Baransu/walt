# Snapshot report for `src/__tests__/memory-spec.js`

The actual snapshot is saved in `memory-spec.js.snap`.

Generated by [AVA](https://ava.li).

## memory store on float arrays

> Snapshot 1

    {
      Type: 'MemoryAssignment',
      meta: [],
      params: [
        {
          Type: 'ArraySubscript',
          meta: [
            {
              payload: 'f32',
              type: 'type/array',
            },
          ],
          params: [
            {
              Type: 'Identifier',
              meta: [
                {
                  payload: 0,
                  type: 'local/index',
                },
              ],
              params: [],
              range: [
                {
                  col: 0,
                  line: 1,
                },
                {
                  col: 1,
                  line: 1,
                },
              ],
              type: 'i32',
              value: 'x',
            },
            {
              Type: 'Constant',
              meta: [],
              params: [],
              range: [
                {
                  col: 2,
                  line: 1,
                },
                {
                  col: 3,
                  line: 1,
                },
              ],
              type: 'i32',
              value: '0',
            },
          ],
          range: [
            undefined,
            {
              col: 4,
              line: 1,
            },
          ],
          type: 'f32',
          value: '[',
        },
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 7,
              line: 1,
            },
            {
              col: 10,
              line: 1,
            },
          ],
          type: 'f32',
          value: '2.0',
        },
      ],
      range: [
        undefined,
        {
          col: 11,
          line: 1,
        },
        {
          col: 11,
          line: 1,
        },
      ],
      type: 'f32',
      value: '=',
    }